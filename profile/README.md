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
    h2 {
      border-left: 6px solid #3b82f6;
      padding-left: 1rem;
      margin-bottom: 1rem;
      color: #111827;
    }
    p {
      line-height: 1.6;
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
    .tech-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
      gap: 1.5rem;
      text-align: center;
      margin-top: 2rem;
    }
    .tech {
      background-color: white;
      border-radius: 10px;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }
    .tech span {
      font-size: 2rem;
    }
    footer {
      background-color: #111827;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>🤖 Sentez Zeka</h1>
    <p>Disiplinlerarası Yapay Zeka Takımı</p>
  </header>

  <section class="section">
    <h2>🧠 Hakkımızda</h2>
    <p>
      Sentez Zeka, farklı mühendislik disiplinlerini ve temel bilimlerin analitik gücünü bir araya getirme felsefesiyle kurulmuş bir yapay zeka takımıdır. 
      Takımımız, insanı anlayan, onunla empati kurabilen ve etik değerlere saygılı çözümler üretmeyi hedeflemektedir.
    </p>
  </section>

  <section class="section">
    <h2>🌟 Vizyonumuz</h2>
    <p>
      İnsan-merkezli, anlayışlı ve sorumlu yapay zeka sistemleri geliştirerek geleceği daha yaşanabilir kılmak.
    </p>

    <h2>🎯 Misyonumuz</h2>
    <p>
      Disiplinlerarası bir yaklaşımla, etik, yenilikçi ve toplum yararına çalışan yapay zeka çözümleri geliştirmek.
    </p>
  </section>

  <section class="section">
    <h2>👥 Takım Üyeleri</h2>
    <div class="team-grid">
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Olaf+Yunus" alt="Olaf Yunus">
        <h3>🧑‍🏫 Dr. Olaf Yunus Laitinen Imanov</h3>
        <p>Danışman – Yapay Zeka Şampiyonu, DTU</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Batuhan+Özdemir" alt="Batuhan Özdemir">
        <h3>🧑‍💻 Batuhan Özdemir</h3>
        <p>Yapay Zeka Geliştirici – Modelleme & Eğitim</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=İrfan+Semih+Doğru" alt="İrfan Semih Doğru">
        <h3>💻 İrfan Semih Doğru</h3>
        <p>Yazılım Geliştirici – Full Stack Developer</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Sümeyye+Nur+Altun" alt="Sümeyye Nur Altun">
        <h3>🗂️ Sümeyye Nur Altun</h3>
        <p>Proje Yönetimi – Planlama & Organizasyon</p>
      </div>
      <div class="member">
        <img src="https://via.placeholder.com/400x250?text=Melike+Nesrin+Zaman" alt="Melike Nesrin Zaman">
        <h3>❤️ Melike Nesrin Zaman</h3>
        <p>Etik & Sosyal Sorumluluk – Empatik AI</p>
      </div>
    </div>
  </section>

  <section class="section" style="background-color:#f3f4f6;">
    <h2>🛠️ Kullandığımız Teknolojiler</h2>
    <div class="tech-grid">
      <div class="tech"><span>🐍</span><br>Python</div>
      <div class="tech"><span>🤖</span><br>TensorFlow</div>
