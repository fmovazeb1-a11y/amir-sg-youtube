# amir-sg-youtube
AMIR SG Youtube

<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#0b1020">
  <title>AMIR SG | Gaming Hub</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Tahoma, Arial, sans-serif;
      background: #0b1020;
      color: #f5f7ff;
      line-height: 1.9;
    }
    header {
      padding: 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #28334c;
    }
    .logo { font-size: 23px; font-weight: bold; }
    .logo span { color: #ff4255; }
    a { color: inherit; text-decoration: none; }
    .hero {
      padding: 75px 20px;
      text-align: center;
      background: radial-gradient(ellipse at top, #203c73, #0b1020 70%);
    }
    .tag {
      color: #ff6575;
      font-weight: bold;
      letter-spacing: 2px;
    }
    h1 { font-size: clamp(38px, 8vw, 68px); margin: 10px 0; }
    h1 span { color: #ff4255; }
    .hero p { color: #c5cee2; max-width: 540px; margin: 15px auto 25px; }
    .btn {
      display: inline-block;
      padding: 11px 22px;
      margin: 5px;
      border-radius: 10px;
      background: #ff4255;
      font-weight: bold;
    }
    .btn.secondary { background: #1b2945; border: 1px solid #425477; }
    main { max-width: 1000px; margin: auto; padding: 30px 18px 55px; }
    h2 { font-size: 25px; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 16px; }
    .card {
      padding: 22px;
      background: #131c30;
      border: 1px solid #293754;
      border-radius: 16px;
    }
    .emoji { font-size: 34px; }
    .card p { color: #bac5db; }
    .about { margin-top: 25px; }
    footer { text-align: center; padding: 25px; color: #aab5cc; border-top: 1px solid #28334c; }
  </style>
</head>
<body>
  <header>
    <a class="logo" href="#">AMIR <span>SG</span></a>
    <a href="#about">درباره کانال</a>
  </header>

  <section class="hero">
    <div class="tag">WELCOME TO MY WORLD</div>
    <h1>AMIR <span>SG</span></h1>
    <p>دنیای گیمینگ، ماینکرفت و پروژه‌های خفن من!
      به سایت رسمی کانال من خوش اومدی.</p>
    <a class="btn" href="https://www.youtube.com/"
       target="_blank" rel="noopener">▶ ورود به یوتیوب</a>
    <a class="btn secondary" href="#projects">پروژه‌های من</a>
  </section>

  <main>
    <h2>🎮 بخش‌های سایت</h2>
    <div class="grid" id="projects">
      <article class="card">
        <div class="emoji">⛏️</div>
        <h3>Minecraft</h3>
        <p>ماجراجویی‌ها، مپ‌ها و پروژه‌های ماینکرفتی AMIR SG.</p>
      </article>
      <article class="card">
        <div class="emoji">📺</div>
        <h3>YouTube</h3>
        <p>ویدیوها و شورت‌های جدید کانال رو اینجا دنبال کن.</p>
      </article>
      <article class="card">
        <div class="emoji">💻</div>
        <h3>My Projects</h3>
        <p>پروژه‌های کامپیوتری و کارهای جدیدی که در آینده منتشر می‌کنم.</p>
      </article>
    </div>

    <section class="card about" id="about">
      <h2>👋 درباره AMIR SG</h2>
      <p>من سازنده کانال AMIR SG هستم.
        این سایت به‌مرور کامل‌تر می‌شه و امکانات جدیدی می‌گیره.
        ممنون که از پروژه‌هام حمایت می‌کنی! ❤️</p>
    </section>
  </main>

  <footer>
    © 2026 AMIR SG — Made with ❤️
  </footer>
</body>
</html>
