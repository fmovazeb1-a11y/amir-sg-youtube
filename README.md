
<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#0b1020">
  <meta name="description" content="سایت رسمی AMIR SG؛ دنیای ماینکرفت، گیمینگ و پروژه‌های کامپیوتری.">
  <title>AMIR SG | Gaming Hub</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    :root {
      --bg: #0b1020;
      --card: #141e33;
      --blue: #438bff;
      --red: #ff4255;
      --white: #f5f7ff;
      --muted: #b9c5dc;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Tahoma, Arial, sans-serif;
      background: var(--bg);
      color: var(--white);
      line-height: 1.9;
    }

    a {
      color: inherit;
      text-decoration: none;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 10;
      padding: 14px 6%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 15px;
      background: #0b1020ed;
      border-bottom: 1px solid #293653;
      backdrop-filter: blur(12px);
    }

    .logo {
      font-size: 24px;
      font-weight: 900;
      direction: ltr;
    }

    .logo span {
      color: var(--red);
    }

    nav {
      display: flex;
      gap: 18px;
      font-size: 13px;
    }

    nav a:hover {
      color: var(--blue);
    }

    .hero {
      padding: 85px 20px 75px;
      text-align: center;
      background:
        radial-gradient(ellipse at 50% 0%, #234a8b 0%, transparent 65%),
        linear-gradient(180deg, #101a30, var(--bg));
    }

    .tag {
      display: inline-block;
      color: #ff8290;
      border: 1px solid #713442;
      border-radius: 30px;
      padding: 3px 15px;
      font-size: 12px;
      letter-spacing: 2px;
      direction: ltr;
    }

    h1 {
      margin: 18px 0 5px;
      font-size: clamp(45px, 10vw, 76px);
      line-height: 1.3;
      direction: ltr;
    }

    h1 span {
      color: var(--red);
    }

    .hero p {
      max-width: 550px;
      margin: 12px auto 25px;
      color: var(--muted);
    }

    .buttons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
    }

    .btn {
      display: inline-block;
      padding: 11px 22px;
      border-radius: 10px;
      background: var(--red);
      color: white;
      font-weight: bold;
      transition: transform .2s, filter .2s;
    }

    .btn:hover {
      transform: translateY(-3px);
      filter: brightness(1.12);
    }

    .btn.secondary {
      background: #192844;
      border: 1px solid #405578;
    }

    main {
      max-width: 1050px;
      margin: auto;
      padding: 38px 20px 65px;
    }

    .section-title {
      font-size: 25px;
      margin-bottom: 18px;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 17px;
    }

    .card {
      padding: 23px;
      border-radius: 16px;
      background: linear-gradient(145deg, #18243b, #111a2c);
      border: 1px solid #2b3a58;
      transition: transform .2s, border-color .2s;
    }

    .card:hover {
      transform: translateY(-4px);
      border-color: var(--blue);
    }

    .emoji {
      font-size: 36px;
      margin-bottom: 6px;
    }

    .card h3 {
      margin-bottom: 7px;
    }

    .card p {
      color: var(--muted);
      font-size: 14px;
    }

    .about {
      margin-top: 30px;
      border-right: 4px solid var(--blue);
    }

    .about h2 {
      margin-bottom: 8px;
    }

    .channel {
      margin-top: 25px;
      text-align: center;
      background: linear-gradient(120deg, #182f59, #311a31);
    }

    .channel p {
      margin: 8px 0 17px;
    }

    footer {
      text-align: center;
      padding: 25px 15px;
      border-top: 1px solid #293653;
      color: var(--muted);
      font-size: 13px;
    }

    footer span {
      color: var(--red);
    }

    @media (max-width: 480px) {
      header {
        padding: 12px 4%;
      }

      .logo {
        font-size: 20px;
      }

      nav {
        gap: 10px;
        font-size: 11px;
      }

      .hero {
        padding-top: 65px;
      }

      main {
        padding-inline: 15px;
      }
    }
  </style>
</head>

<body>

  <header>
    <a class="logo" href="#">AMIR <span>SG</span></a>

    <nav>
      <a href="#projects">پروژه‌ها</a>
      <a href="#about">درباره من</a>
      <a href="#channel">یوتیوب</a>
    </nav>
  </header>

  <section class="hero">
    <div class="tag">WELCOME TO MY WORLD</div>

    <h1>AMIR <span>SG</span></h1>

    <p>
      به دنیای گیمینگ من خوش اومدی!
      اینجا قراره ماینکرفت، ویدیوهای یوتیوب
      و پروژه‌های کامپیوتری رو کنار هم داشته باشیم.
    </p>

    <div class="buttons">
      <a class="btn"
         href="https://www.youtube.com/@AmirHoseinMovazeb"
         target="_blank"
         rel="noopener noreferrer">
        ▶ ورود به کانال یوتیوب
      </a>

      <a class="btn secondary" href="#projects">
        🎮 دیدن پروژه‌ها
      </a>
    </div>
  </section>

  <main>
    <section id="projects">
      <h2 class="section-title">🔥 بخش‌های سایت</h2>

      <div class="grid">

        <article class="card">
          <div class="emoji">⛏️</div>
          <h3>Minecraft</h3>
          <p>
            دنیای ماینکرفت، ماجراجویی‌ها،
            مپ‌ها و ایده‌های جدید AMIR SG.
          </p>
        </article>

        <article class="card">
          <div class="emoji">🎬</div>
          <h3>YouTube Videos</h3>
          <p>
            ویدیوها و شورت‌های کانال رو دنبال کن
            و از ویدیوهای جدید باخبر شو.
          </p>
          <br>
          <a class="btn"
             href="https://www.youtube.com/@AmirHoseinMovazeb"
             target="_blank"
             rel="noopener noreferrer">
            دیدن کانال
          </a>
        </article>

        <article class="card">
          <div class="emoji">💻</div>
          <h3>My Projects</h3>
          <p>
            پروژه‌های برنامه‌نویسی،
            ایده‌های کامپیوتری و کارهای آیندهٔ من.
          </p>
        </article>

      </div>
    </section>

    <section class="card about" id="about">
      <h2>👋 درباره AMIR SG</h2>
      <p>
        من سازندهٔ کانال AMIR SG هستم.
        این سایت رو برای معرفی کانال، بازی‌ها
        و پروژه‌های خودم ساختم.
        اینجا تازه شروع ماجراست! ❤️‍🔥
      </p>
    </section>

    <section class="card channel" id="channel">
      <div class="emoji">🔴</div>
      <h2>به خانوادهٔ AMIR SG بپیوند!</h2>
      <p>
        برای دیدن ویدیوها و شورت‌های من،
        وارد کانال یوتیوب شو.
      </p>

      <a class="btn"
         href="https://www.youtube.com/@AmirHoseinMovazeb"
         target="_blank"
         rel="noopener noreferrer">
        ▶ باز کردن کانال AMIR SG
      </a>
    </section>
  </main>

  <footer>
    © 2026 AMIR SG — ساخته‌شده با <span>❤️</span>
  </footer>

</body>
</html>
