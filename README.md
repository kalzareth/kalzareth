<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <title>دو زبانه</title>
  <style>
    body {
      direction: rtl;
      font-family: sans-serif;
      text-align: center;
    }
    .lang-btn {
      margin: 10px;
      padding: 8px 16px;
      border: none;
      background-color: #2E9EF7;
      color: white;
      border-radius: 8px;
      cursor: pointer;
    }
    [data-lang] { display: none; }
    [data-lang="fa"] { direction: rtl; }
    [data-lang="en"] { direction: ltr; }
  </style>
</head>
<body>
  <div>
    <button class="lang-btn" onclick="setLang('fa')">🇮🇷 فارسی</button>
    <button class="lang-btn" onclick="setLang('en')">🇬🇧 English</button>
  </div>

  <!-- Persian Section -->
  <div data-lang="fa">
    <div align="center">
      <img src="https://readme-typing-svg.herokuapp.com?font=Vazir&size=35&pause=1000&color=2E9EF7&center=true&vCenter=true&width=500&lines=سلام!+من+امیر+هستم+👋;برنامه‌نویس+و+طراح;عاشق+یادگیری+و+خلاقیت" alt="Typing SVG" />
    </div>
    👨‍💻 علاقه مند به دنیای تکنولوژی، طراحی و کدنویسی.  
    در حال یادگیری و ساختن مسیر . . .
    <hr>
    <h2>🚀 درباره من</h2>
    🎨 علاقه‌مند به طراحی UI/UX و کار با Figma  
    💻 در حال یادگیری Python و JavaScript  
    🔐 امنیت سایبری و تست نفوذ  
    🌱 همیشه دنبال یاد گرفتن
    <hr>
    <h2>🛠️ مهارت‌ها و ابزارها</h2>
    <div align="center">
      <h3>🎨 طراحی رابط کاربری</h3>
      <img src="https://skillicons.dev/icons?i=figma" alt="Figma" width="50" height="50"/>
      <h3>💻 در حال یادگیری این زبان‌ها</h3>
      <img src="https://skillicons.dev/icons?i=python,js" alt="Python, JavaScript" width="110" height="50"/>
      <h3>🔐 سیستم‌عامل‌ها و مفاهیم امنیتی</h3>
      <img src="https://skillicons.dev/icons?i=linux" alt="Linux" width="50" height="50"/>
    </div>
    <hr>
    <h2>🤝 راه‌های ارتباطی</h2>
    <div align="center">
      <a href="https://t.me/Kalzareth"><img src="https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white"></a>
      <a href="mailto:kalzareth@proton.me"><img src="https://img.shields.io/badge/Email-8B89CC?logo=protonmail&logoColor=white"></a>
    </div>
    <hr>
    <div align="center">
      <img src="https://komarev.com/ghpvc/?username=Kalzareth&label=بازدید%20پروفایل&color=0e75b6&style=flat" alt="Profile Views" />
      <h3>💫 «با یادگیری، ساختن، و اشتراک‌گذاری رشد می‌کنم!»</h3>
    </div>
    <hr>
    <div align="center">
      <img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg" width="100%" />
    </div>
  </div>

  <!-- English Section -->
  <div data-lang="en">
    <div align="center">
      <img src="https://readme-typing-svg.herokuapp.com?font=Vazir&size=35&pause=1000&color=2E9EF7&center=true&vCenter=true&width=500&lines=Hello!+I+am+Amir+👋;Programmer+and+Designer;Passionate+about+learning+and+creativity" alt="Typing SVG" />
    </div>
    👨‍💻 Passionate about technology, design, and coding.  
    Currently learning and building the path . . .
    <hr>
    <h2>🚀 About Me</h2>
    🎨 Interested in UI/UX design and working with Figma  
    💻 Learning Python and JavaScript  
    🔐 Cybersecurity and penetration testing  
    🌱 Always eager to learn
    <hr>
    <h2>🛠️ Skills & Tools</h2>
    <div align="center">
      <h3>🎨 UI Design</h3>
      <img src="https://skillicons.dev/icons?i=figma" alt="Figma" width="50" height="50"/>
      <h3>💻 Currently Learning</h3>
      <img src="https://skillicons.dev/icons?i=python,js" alt="Python, JavaScript" width="110" height="50"/>
      <h3>🔐 OS & Security Concepts</h3>
      <img src="https://skillicons.dev/icons?i=linux" alt="Linux" width="50" height="50"/>
    </div>
    <hr>
    <h2>🤝 Contact</h2>
    <div align="center">
      <a href="https://t.me/Kalzareth"><img src="https://img.shields.io/badge/Telegram-2CA5E0?logo=telegram&logoColor=white"></a>
      <a href="mailto:kalzareth@proton.me"><img src="https://img.shields.io/badge/Email-8B89CC?logo=protonmail&logoColor=white"></a>
    </div>
    <hr>
    <div align="center">
      <img src="https://komarev.com/ghpvc/?username=Kalzareth&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
      <h3>💫 “I grow by learning, building, and sharing!”</h3>
    </div>
    <hr>
    <div align="center">
      <img src="https://raw.githubusercontent.com/platane/platane/output/github-contribution-grid-snake-dark.svg" width="100%" />
    </div>
  </div>

  <script>
    function setLang(lang) {
      document.querySelectorAll('[data-lang]').forEach(el => {
        el.style.display = el.getAttribute('data-lang') === lang ? 'block' : 'none';
      });
    }
    // پیش‌فرض فارسی
    setLang('fa');
  </script>
</body>
</html>
