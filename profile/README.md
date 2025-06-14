<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sentez Zeka - Takım Tanıtımı</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9fafb;
      color: #1f2937;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #111827;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    h1 {
      margin-bottom: 0.5rem;
    }
    .section {
      padding: 3rem 2rem;
      max-width: 1100px;
      margin: auto;
    }
    .team-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .member {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
      overflow: hidden;
      text-align: center;
      padding-bottom: 1rem;
    }
    .member img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .member h3 {
      margin: 1rem 0 0.5rem;
    }
    .member p {
      padding: 0 1rem;
      font-size: 0.95rem;
      color: #555;
    }
    .advisor {
      margin-top: 4rem;
      text-align: center;
    }
    .advisor img {
      width: 160px;
      border-radius: 50%;
      margin-bottom: 1rem;
    }
    footer {
      background-color: #111827;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sentez Zeka</h1>
    <p>Disiplinlerarası Gücün Buluştuğu Yapay Zeka Takımı</p>
  </header>

  <section class="section">
    <h2>Hakkımızda</h2>
    <p>
      Sentez Zeka, adını farklı mühendislik disiplinleri ile temel bilimlerin analitik gücünü bir araya getiren felsefesinden alır.
      Ekibimiz, yapay zekanın insanla empati kurabilen yönünü ön plana çıkararak geleceğin teknolojisini şekillendirmeyi hedefler.
    </p>

    <div class="team-grid">
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Emre+Rodoplu" alt="Emre Rodoplu">
        <h3>Emre Rodoplu</h3>
        <p>Takım Kaptanı & Matematikçi<br/>Analitik Liderlik</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Giray+Yurtseven" alt="Giray Yurtseven">
        <h3>Giray Yurtseven</h3>
        <p>Proje Yöneticisi<br/>Teknofest Roket Yarışması Deneyimi</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Şölə+Əmiyeva" alt="Şölə Əmiyeva">
        <h3>Şölə Əmiyeva</h3>
        <p>Startup Uzmanı<br/>COP29 ve Hackathon Başarıları</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Ozan+Mühürcü" alt="Ozan Mühürcü">
        <h3>Ozan Mühürcü</h3>
        <p>Endüstri Mühendisi<br/>Süreç Optimizasyonu</p>
      </div>
    </div>

    <div class="advisor">
      <h2>Akademik Danışmanımız</h2>
      <img src="https://via.placeholder.com/160?text=Olaf+Yunus" alt="Olaf Yunus">
      <h3>Dr. Olaf Yunus Laitinen Imanov</h3>
      <p>Danimarka Teknik Üniversitesi<br/>Yapay Zeka Uzmanı | Uluslararası Şampiyon</p>
    </div>
  </section>

  <section class="section" style="background-color:#f3f4f6;">
    <h2>Projemiz: EmpatiBOT</h2>
    <p>
      EmpatiBOT, insanı anlayan ve onunla empati kuran bir yapay zeka çözümüdür. Analitik zekânın duygusal zekâ ile buluştuğu bu
      proje; yapay zekanın sadece hesaplayan değil, hisseden bir dost olmasını amaçlamaktadır.
    </p>
    <img src="https://via.placeholder.com/1000x400?text=EmpatiBOT+Projesi" alt="EmpatiBOT Projesi" style="width:100%; border-radius: 10px; margin-top: 1rem;">
  </section>

  <footer>
    <p>&copy; 2025 Sentez Zeka Takımı | Tüm Hakları Saklıdır</p>
  </footer>

</body>
</html>
