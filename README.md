<div align="center">

<svg width="900" height="280" viewBox="0 0 900 280" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="hbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818">
        <animate attributeName="stop-color" values="#020818;#0a1628;#020818" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#0d1f3c">
        <animate attributeName="stop-color" values="#0d1f3c;#1a3a6e;#0d1f3c" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#050d1a">
        <animate attributeName="stop-color" values="#050d1a;#0d1f3c;#050d1a" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="cyanglow" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00d9ff;stop-opacity:0.9"/>
      <stop offset="70%" style="stop-color:#7b61ff;stop-opacity:0.9"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
    <linearGradient id="textgrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2">
        <animate attributeName="stop-color" values="#00fff2;#7b61ff;#ff61d8;#00fff2" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" style="stop-color:#7b61ff">
        <animate attributeName="stop-color" values="#7b61ff;#ff61d8;#00fff2;#7b61ff" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#ff61d8">
        <animate attributeName="stop-color" values="#ff61d8;#00fff2;#7b61ff;#ff61d8" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <filter id="blur3">
      <feGaussianBlur stdDeviation="3"/>
    </filter>
    <filter id="blur8">
      <feGaussianBlur stdDeviation="8"/>
    </filter>
    <filter id="blur15">
      <feGaussianBlur stdDeviation="15"/>
    </filter>
    <filter id="textglow">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="subtleglow">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect width="900" height="280" fill="url(#hbg)" rx="16"/>

  <ellipse cx="150" cy="80" rx="120" ry="80" fill="#00d9ff" opacity="0.06" filter="url(#blur15)">
    <animate attributeName="cx" values="150;200;150" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.06;0.12;0.06" dur="8s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="750" cy="180" rx="140" ry="90" fill="#7b61ff" opacity="0.08" filter="url(#blur15)">
    <animate attributeName="cx" values="750;700;750" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.08;0.15;0.08" dur="7s" repeatCount="indefinite"/>
  </ellipse>
  <ellipse cx="450" cy="260" rx="200" ry="60" fill="#ff61d8" opacity="0.05" filter="url(#blur15)">
    <animate attributeName="ry" values="60;90;60" dur="9s" repeatCount="indefinite"/>
  </ellipse>

  <circle cx="80" cy="50" r="1.5" fill="#00fff2" opacity="0.8"><animate attributeName="opacity" values="0.8;0.1;0.8" dur="2.3s" repeatCount="indefinite"/><animate attributeName="r" values="1.5;2.5;1.5" dur="2.3s" repeatCount="indefinite"/></circle>
  <circle cx="180" cy="220" r="1" fill="#7b61ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="1.8s" repeatCount="indefinite"/></circle>
  <circle cx="320" cy="30" r="2" fill="#ff61d8" opacity="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="3.1s" repeatCount="indefinite"/><animate attributeName="r" values="2;3;2" dur="3.1s" repeatCount="indefinite"/></circle>
  <circle cx="500" cy="250" r="1.5" fill="#00d9ff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="2.7s" repeatCount="indefinite"/></circle>
  <circle cx="650" cy="40" r="1" fill="#00fff2" opacity="0.9"><animate attributeName="opacity" values="0.9;0.2;0.9" dur="1.5s" repeatCount="indefinite"/></circle>
  <circle cx="820" cy="120" r="2" fill="#7b61ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="2.9s" repeatCount="indefinite"/><animate attributeName="r" values="2;3.5;2" dur="2.9s" repeatCount="indefinite"/></circle>
  <circle cx="860" cy="240" r="1.5" fill="#ff61d8" opacity="0.5"><animate attributeName="opacity" values="0.5;1;0.5" dur="2.1s" repeatCount="indefinite"/></circle>
  <circle cx="40" cy="180" r="1" fill="#7b61ff" opacity="0.7"><animate attributeName="opacity" values="0.7;0.1;0.7" dur="3.4s" repeatCount="indefinite"/></circle>
  <circle cx="730" cy="260" r="1.5" fill="#00d9ff" opacity="0.6"><animate attributeName="opacity" values="0.6;0.2;0.6" dur="2.0s" repeatCount="indefinite"/></circle>
  <circle cx="250" cy="150" r="1" fill="#ff61d8" opacity="0.4"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="4.2s" repeatCount="indefinite"/></circle>

  <rect x="0" y="255" width="900" height="4" fill="url(#cyanglow)">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="255" width="900" height="4" fill="url(#cyanglow)" filter="url(#blur3)" opacity="0.8">
    <animate attributeName="opacity" values="0.4;0.9;0.4" dur="3s" repeatCount="indefinite"/>
  </rect>

  <text x="450" y="108" font-family="'Segoe UI',Arial,sans-serif" font-size="52" font-weight="800" fill="url(#textgrad)" text-anchor="middle" filter="url(#textglow)" letter-spacing="2">Siva Prasanna S</text>
  <text x="450" y="108" font-family="'Segoe UI',Arial,sans-serif" font-size="52" font-weight="800" fill="url(#textgrad)" text-anchor="middle" opacity="0.3" filter="url(#blur8)" letter-spacing="2">Siva Prasanna S</text>

  <text x="450" y="148" font-family="'Segoe UI',Arial,sans-serif" font-size="17" fill="#94a3b8" text-anchor="middle" filter="url(#subtleglow)" letter-spacing="3">FULL-STACK DEVELOPER  ·  CLOUD ENGINEER</text>

  <rect x="200" y="162" width="500" height="1" fill="url(#cyanglow)" opacity="0.6">
    <animate attributeName="width" values="0;500;0" dur="4s" repeatCount="indefinite" begin="0s"/>
    <animate attributeName="x" values="450;200;450" dur="4s" repeatCount="indefinite" begin="0s"/>
  </rect>

  <text x="450" y="195" font-family="'Courier New',monospace" font-size="13" fill="#00d9ff" text-anchor="middle" opacity="0.9" letter-spacing="1">
    <tspan>MEAN</tspan>
    <tspan fill="#7b61ff" dx="8">|</tspan>
    <tspan fill="#94a3b8" dx="8">MERN</tspan>
    <tspan fill="#7b61ff" dx="8">|</tspan>
    <tspan fill="#94a3b8" dx="8">Java</tspan>
    <tspan fill="#7b61ff" dx="8">|</tspan>
    <tspan fill="#94a3b8" dx="8">Spring Boot</tspan>
    <tspan fill="#7b61ff" dx="8">|</tspan>
    <tspan fill="#00d9ff" dx="8">AWS ☁</tspan>
  </text>

  <text x="450" y="230" font-family="'Courier New',monospace" font-size="11" fill="#7b61ff" text-anchor="middle" opacity="0.7" letter-spacing="2">
    <animate attributeName="opacity" values="0.7;0.3;0.7" dur="2s" repeatCount="indefinite"/>
    ◈ MICROSERVICES · DOCKER · KAFKA · KUBERNETES ◈
  </text>
</svg>

</div>

<div align="center">

![](https://komarev.com/ghpvc/?username=SivaPrasannaS&label=Profile+Views&color=7b61ff&style=flat-square)
&nbsp;
[![](https://img.shields.io/github/followers/SivaPrasannaS?label=Followers&style=flat-square&color=00d9ff&labelColor=0d1117)](https://github.com/SivaPrasannaS)
&nbsp;
[![](https://img.shields.io/github/stars/SivaPrasannaS?affiliations=OWNER&style=flat-square&color=ff61d8&labelColor=0d1117&label=Stars)](https://github.com/SivaPrasannaS)
&nbsp;
![](https://img.shields.io/badge/AWS-Certified_CLF--C02-FF9900?style=flat-square&logo=amazonaws&logoColor=white&labelColor=0d1117)
&nbsp;
![](https://img.shields.io/badge/Open_To-Opportunities-00d9ff?style=flat-square&labelColor=0d1117)

</div>

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="linegrad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff;stop-opacity:1"/>
      <stop offset="75%" style="stop-color:#7b61ff;stop-opacity:1"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#linegrad2)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  ABOUT ME  ◈</text>
</svg>

</div>

<br/>

```
  Architecting scalable systems from pixel-perfect UIs to bulletproof backends.
  Passionate about clean architecture, event-driven microservices, and cloud-native solutions.
```

- 🔭 &nbsp;Building **production-ready full-stack applications** with React, Spring Boot & Microservices
- 🌩️ &nbsp;**AWS Certified Cloud Practitioner (CLF-C02)** ✅ — actively exploring cloud-native patterns
- 🧩 &nbsp;Deep expertise in **JWT security**, **RBAC**, **Spring Cloud**, **Kafka**, **Docker**
- 🗄️ &nbsp;Comfortable across **MySQL · PostgreSQL · MongoDB**
- 📖 &nbsp;Currently levelling up in **Kubernetes** and **system design**
- ⚡ &nbsp;I debug with coffee ☕ and deploy with confidence 🚀

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="lg2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff"/>
      <stop offset="75%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg2)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#lg2)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  TECH STACK  ◈</text>
</svg>

</div>

<br/>
<div align="center">

![React](https://img.shields.io/badge/React-0d1117?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-0d1117?style=for-the-badge&logo=angular&logoColor=DD0031)
![TypeScript](https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-0d1117?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TailwindCSS](https://img.shields.io/badge/Tailwind-0d1117?style=for-the-badge&logo=tailwindcss&logoColor=06B6D4)
![Redux](https://img.shields.io/badge/Redux-0d1117?style=for-the-badge&logo=redux&logoColor=764ABC)

![Java](https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=ED8B00)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-0d1117?style=for-the-badge&logo=springboot&logoColor=6DB33F)
![Spring Security](https://img.shields.io/badge/Spring_Security-0d1117?style=for-the-badge&logo=springsecurity&logoColor=6DB33F)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-0d1117?style=for-the-badge&logo=spring&logoColor=6DB33F)
![Node.js](https://img.shields.io/badge/Node.js-0d1117?style=for-the-badge&logo=node.js&logoColor=339933)
![Express](https://img.shields.io/badge/Express-0d1117?style=for-the-badge&logo=express&logoColor=ffffff)

![Kafka](https://img.shields.io/badge/Kafka-0d1117?style=for-the-badge&logo=apachekafka&logoColor=ffffff)
![Docker](https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=2496ED)
![AWS](https://img.shields.io/badge/AWS-0d1117?style=for-the-badge&logo=amazonaws&logoColor=FF9900)
![MySQL](https://img.shields.io/badge/MySQL-0d1117?style=for-the-badge&logo=mysql&logoColor=4479A1)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=4169E1)
![MongoDB](https://img.shields.io/badge/MongoDB-0d1117?style=for-the-badge&logo=mongodb&logoColor=47A248)
![Git](https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=F05032)
![Maven](https://img.shields.io/badge/Maven-0d1117?style=for-the-badge&logo=apachemaven&logoColor=C71A36)

</div>

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="lg3" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff"/>
      <stop offset="75%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg3)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#lg3)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  CERTIFICATIONS  ◈</text>
</svg>

<br/>

<svg width="820" height="90" viewBox="0 0 820 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="certbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#1a1f2e"/>
    </linearGradient>
    <linearGradient id="certborder" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#FF9900;stop-opacity:0.8"/>
      <stop offset="100%" style="stop-color:#ffcc00;stop-opacity:0.8"/>
    </linearGradient>
    <filter id="certglow">
      <feGaussianBlur stdDeviation="4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="820" height="90" rx="12" fill="url(#certbg)" stroke="url(#certborder)" stroke-width="1"/>
  <rect width="820" height="90" rx="12" fill="none" stroke="url(#certborder)" stroke-width="1" opacity="0.4" filter="url(#certglow)"/>
  <rect x="0" y="0" width="5" height="90" rx="2" fill="url(#certborder)"/>
  <text x="30" y="38" font-family="'Segoe UI',Arial,sans-serif" font-size="18" fill="#FF9900" filter="url(#certglow)">☁</text>
  <text x="58" y="36" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="700" fill="#e2e8f0">AWS Certified Cloud Practitioner</text>
  <text x="58" y="56" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#94a3b8">CLF-C02  ·  Amazon Web Services  ·  2025</text>
  <rect x="630" y="28" width="80" height="24" rx="12" fill="#FF9900" opacity="0.15" stroke="#FF9900" stroke-width="0.5"/>
  <text x="670" y="44" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#FF9900" text-anchor="middle" font-weight="600">✓ VERIFIED</text>
  <text x="724" y="44" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#00d9ff" text-anchor="middle">Credly ↗</text>
</svg>

</div>

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="lg4" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff"/>
      <stop offset="75%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg4)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#lg4)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  FEATURED PROJECTS  ◈</text>
</svg>

<br/>

<svg width="900" height="340" viewBox="0 0 900 340" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="pb1" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f2d1a"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="pb2" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2d1a0f"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="pb3" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1a0f2d"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="pb4" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#2d0f1a"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="gg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6DB33F"/>
      <stop offset="100%" style="stop-color:#4ade80"/>
    </linearGradient>
    <linearGradient id="og" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ED8B00"/>
      <stop offset="100%" style="stop-color:#fbbf24"/>
    </linearGradient>
    <linearGradient id="vg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#a78bfa"/>
    </linearGradient>
    <linearGradient id="pg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#ff61d8"/>
      <stop offset="100%" style="stop-color:#fb7185"/>
    </linearGradient>
    <filter id="cardglow1">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <rect x="0" y="0" width="435" height="155" rx="12" fill="url(#pb1)" stroke="#6DB33F" stroke-width="0.5" opacity="0.9"/>
  <rect x="0" y="0" width="435" height="5" rx="3" fill="url(#gg)"/>
  <rect x="0" y="0" width="435" height="155" rx="12" fill="none" stroke="#6DB33F" stroke-width="1" opacity="0.2" filter="url(#cardglow1)"/>
  <text x="20" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="700" fill="#4ade80">🔐  spring-security</text>
  <rect x="355" y="16" width="64" height="20" rx="10" fill="#6DB33F" opacity="0.15" stroke="#6DB33F" stroke-width="0.5"/>
  <text x="387" y="30" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#6DB33F" text-anchor="middle">⭐  2 stars</text>
  <text x="20" y="58" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">JWT-based authentication · Role-based access control</text>
  <text x="20" y="76" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Spring Security filters · Dockerized deployment</text>
  <rect x="20" y="95" width="48" height="20" rx="10" fill="#ED8B00" opacity="0.15"/><text x="44" y="109" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#ED8B00" text-anchor="middle">Java</text>
  <rect x="76" y="95" width="80" height="20" rx="10" fill="#6DB33F" opacity="0.15"/><text x="116" y="109" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#6DB33F" text-anchor="middle">Spring Boot</text>
  <rect x="164" y="95" width="58" height="20" rx="10" fill="#2496ED" opacity="0.15"/><text x="193" y="109" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#2496ED" text-anchor="middle">Docker</text>
  <rect x="20" y="126" width="100" height="1" fill="url(#gg)" opacity="0.4"/>
  <text x="20" y="146" font-family="'Courier New',monospace" font-size="11" fill="#6DB33F" opacity="0.7">github.com/SivaPrasannaS/spring-security ↗</text>

  <rect x="465" y="0" width="435" height="155" rx="12" fill="url(#pb2)" stroke="#ED8B00" stroke-width="0.5" opacity="0.9"/>
  <rect x="465" y="0" width="435" height="5" rx="3" fill="url(#og)"/>
  <rect x="465" y="0" width="435" height="155" rx="12" fill="none" stroke="#ED8B00" stroke-width="1" opacity="0.2" filter="url(#cardglow1)"/>
  <text x="485" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="700" fill="#fbbf24">🎟️  Event-Hub</text>
  <rect x="835" y="16" width="48" height="20" rx="10" fill="#3fb950" opacity="0.15" stroke="#3fb950" stroke-width="0.5"/>
  <text x="859" y="30" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#3fb950" text-anchor="middle">● Live</text>
  <text x="485" y="58" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Event management platform · RESTful APIs</text>
  <text x="485" y="76" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Event creation · Registration · Listing system</text>
  <rect x="485" y="95" width="48" height="20" rx="10" fill="#ED8B00" opacity="0.15"/><text x="509" y="109" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#ED8B00" text-anchor="middle">Java</text>
  <rect x="541" y="95" width="80" height="20" rx="10" fill="#6DB33F" opacity="0.15"/><text x="581" y="109" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#6DB33F" text-anchor="middle">Spring Boot</text>
  <rect x="485" y="126" width="100" height="1" fill="url(#og)" opacity="0.4"/>
  <text x="485" y="146" font-family="'Courier New',monospace" font-size="11" fill="#ED8B00" opacity="0.7">github.com/SivaPrasannaS/Event-Hub ↗</text>

  <rect x="0" y="175" width="435" height="155" rx="12" fill="url(#pb3)" stroke="#7b61ff" stroke-width="0.5" opacity="0.9"/>
  <rect x="0" y="175" width="435" height="5" rx="3" fill="url(#vg)"/>
  <rect x="0" y="175" width="435" height="155" rx="12" fill="none" stroke="#7b61ff" stroke-width="1" opacity="0.2" filter="url(#cardglow1)"/>
  <text x="20" y="210" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="700" fill="#a78bfa">📝  Blog-Application</text>
  <rect x="340" y="191" width="78" height="20" rx="10" fill="#7b61ff" opacity="0.15" stroke="#7b61ff" stroke-width="0.5"/>
  <text x="379" y="205" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#a78bfa" text-anchor="middle">Full-Stack</text>
  <text x="20" y="233" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Full-stack blog · CRUD · JWT auth · Rich text</text>
  <text x="20" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Dynamic content rendering · Responsive UI</text>
  <rect x="20" y="270" width="80" height="20" rx="10" fill="#F7DF1E" opacity="0.15"/><text x="60" y="284" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#F7DF1E" text-anchor="middle">JavaScript</text>
  <rect x="108" y="270" width="60" height="20" rx="10" fill="#339933" opacity="0.15"/><text x="138" y="284" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#339933" text-anchor="middle">Node.js</text>
  <rect x="20" y="301" width="100" height="1" fill="url(#vg)" opacity="0.4"/>
  <text x="20" y="321" font-family="'Courier New',monospace" font-size="11" fill="#7b61ff" opacity="0.7">github.com/SivaPrasannaS/Blog-Application ↗</text>

  <rect x="465" y="175" width="435" height="155" rx="12" fill="url(#pb4)" stroke="#ff61d8" stroke-width="0.5" opacity="0.9"/>
  <rect x="465" y="175" width="435" height="5" rx="3" fill="url(#pg)"/>
  <rect x="465" y="175" width="435" height="155" rx="12" fill="none" stroke="#ff61d8" stroke-width="1" opacity="0.2" filter="url(#cardglow1)"/>
  <text x="485" y="210" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="700" fill="#fb7185">📦  Content-Hub-Manager</text>
  <rect x="800" y="191" width="78" height="20" rx="10" fill="#ff61d8" opacity="0.15" stroke="#ff61d8" stroke-width="0.5"/>
  <text x="839" y="205" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#fb7185" text-anchor="middle">Full-Stack</text>
  <text x="485" y="233" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Centralized CMS · RBAC · Content categorization</text>
  <text x="485" y="251" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Responsive React UI · Content workflows</text>
  <rect x="485" y="270" width="80" height="20" rx="10" fill="#F7DF1E" opacity="0.15"/><text x="525" y="284" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#F7DF1E" text-anchor="middle">JavaScript</text>
  <rect x="573" y="270" width="52" height="20" rx="10" fill="#61DAFB" opacity="0.15"/><text x="599" y="284" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#61DAFB" text-anchor="middle">React</text>
  <rect x="485" y="301" width="100" height="1" fill="url(#pg)" opacity="0.4"/>
  <text x="485" y="321" font-family="'Courier New',monospace" font-size="11" fill="#ff61d8" opacity="0.7">github.com/SivaPrasannaS/Content-Hub-Manager ↗</text>
</svg>

</div>

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="lg5" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff"/>
      <stop offset="75%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg5)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#lg5)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  GITHUB STATS  ◈</text>
</svg>

<br/>

<svg width="900" height="130" viewBox="0 0 900 130" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="statbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0d1f3c"/>
    </linearGradient>
    <linearGradient id="stat1" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#00d9ff"/>
      <stop offset="100%" style="stop-color:#7b61ff"/>
    </linearGradient>
    <linearGradient id="stat2" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8"/>
    </linearGradient>
    <linearGradient id="stat3" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#ff61d8"/>
      <stop offset="100%" style="stop-color:#00d9ff"/>
    </linearGradient>
    <filter id="sg">
      <feGaussianBlur stdDeviation="5" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="130" rx="14" fill="url(#statbg)" stroke="#1e293b" stroke-width="1"/>
  <line x1="300" y1="20" x2="300" y2="110" stroke="#1e293b" stroke-width="1"/>
  <line x1="600" y1="20" x2="600" y2="110" stroke="#1e293b" stroke-width="1"/>

  <text x="150" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" fill="url(#stat1)" text-anchor="middle" filter="url(#sg)">103+</text>
  <text x="150" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" fill="url(#stat1)" text-anchor="middle">103+</text>
  <text x="150" y="76" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#00d9ff" text-anchor="middle" letter-spacing="1">CONTRIBUTIONS</text>
  <text x="150" y="96" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#475569" text-anchor="middle">Jul 2023 – Present</text>

  <text x="450" y="48" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" text-anchor="middle" filter="url(#sg)">
    <animate attributeName="fill" values="#7b61ff;#a855f7;#c084fc;#ff61d8;#a855f7;#7b61ff" dur="2s" repeatCount="indefinite"/>
    1 🔥
  </text>
  <text x="450" y="48" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" fill="#a855f7" text-anchor="middle">1 🔥</text>
  <text x="450" y="76" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#a855f7" text-anchor="middle" font-weight="700" letter-spacing="1">CURRENT STREAK</text>
  <text x="450" y="96" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#475569" text-anchor="middle">May 15, 2026</text>

  <text x="750" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" fill="url(#stat3)" text-anchor="middle" filter="url(#sg)">3</text>
  <text x="750" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="36" font-weight="800" fill="url(#stat3)" text-anchor="middle">3</text>
  <text x="750" y="76" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#3fb950" text-anchor="middle" letter-spacing="1">LONGEST STREAK</text>
  <text x="750" y="96" font-family="'Segoe UI',Arial,sans-serif" font-size="10" fill="#475569" text-anchor="middle">Jan 29 – Jan 31, 2024</text>
</svg>

<br/><br/>

<svg width="900" height="290" viewBox="0 0 900 290" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="skillbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0d1f3c"/>
    </linearGradient>
    <linearGradient id="bj" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#ED8B00"/><stop offset="100%" style="stop-color:#fbbf24"/></linearGradient>
    <linearGradient id="bjs" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#F7DF1E"/><stop offset="100%" style="stop-color:#fde68a"/></linearGradient>
    <linearGradient id="bsb" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#6DB33F"/><stop offset="100%" style="stop-color:#86efac"/></linearGradient>
    <linearGradient id="br" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#61DAFB"/><stop offset="100%" style="stop-color:#7dd3fc"/></linearGradient>
    <linearGradient id="bts" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#3178C6"/><stop offset="100%" style="stop-color:#93c5fd"/></linearGradient>
    <linearGradient id="bn" x1="0%" y1="0%" x2="100%" y2="0%"><stop offset="0%" style="stop-color:#339933"/><stop offset="100%" style="stop-color:#86efac"/></linearGradient>
    <filter id="barg">
      <feGaussianBlur stdDeviation="3" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="290" rx="14" fill="url(#skillbg)" stroke="#1e293b" stroke-width="1"/>
  <text x="30" y="36" font-family="'Segoe UI',Arial,sans-serif" font-size="13" font-weight="600" fill="#e2e8f0" letter-spacing="2">LANGUAGE PROFICIENCY</text>

  <text x="30" y="72" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Java</text>
  <rect x="120" y="60" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="60" width="0" height="14" rx="7" fill="url(#bj)" filter="url(#barg)"><animate attributeName="width" from="0" to="648" dur="1.4s" fill="freeze" begin="0.1s"/></rect>
  <rect x="120" y="60" width="0" height="14" rx="7" fill="url(#bj)"><animate attributeName="width" from="0" to="648" dur="1.4s" fill="freeze" begin="0.1s"/></rect>
  <text x="855" y="72" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#ED8B00" text-anchor="end">90%</text>

  <text x="30" y="112" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">JavaScript</text>
  <rect x="120" y="100" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="100" width="0" height="14" rx="7" fill="url(#bjs)" filter="url(#barg)"><animate attributeName="width" from="0" to="612" dur="1.4s" fill="freeze" begin="0.3s"/></rect>
  <rect x="120" y="100" width="0" height="14" rx="7" fill="url(#bjs)"><animate attributeName="width" from="0" to="612" dur="1.4s" fill="freeze" begin="0.3s"/></rect>
  <text x="855" y="112" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#F7DF1E" text-anchor="end">85%</text>

  <text x="30" y="152" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Spring Boot</text>
  <rect x="120" y="140" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="140" width="0" height="14" rx="7" fill="url(#bsb)" filter="url(#barg)"><animate attributeName="width" from="0" to="576" dur="1.4s" fill="freeze" begin="0.5s"/></rect>
  <rect x="120" y="140" width="0" height="14" rx="7" fill="url(#bsb)"><animate attributeName="width" from="0" to="576" dur="1.4s" fill="freeze" begin="0.5s"/></rect>
  <text x="855" y="152" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#6DB33F" text-anchor="end">80%</text>

  <text x="30" y="192" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">React</text>
  <rect x="120" y="180" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="180" width="0" height="14" rx="7" fill="url(#br)" filter="url(#barg)"><animate attributeName="width" from="0" to="540" dur="1.4s" fill="freeze" begin="0.7s"/></rect>
  <rect x="120" y="180" width="0" height="14" rx="7" fill="url(#br)"><animate attributeName="width" from="0" to="540" dur="1.4s" fill="freeze" begin="0.7s"/></rect>
  <text x="855" y="192" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#61DAFB" text-anchor="end">75%</text>

  <text x="30" y="232" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">TypeScript</text>
  <rect x="120" y="220" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="220" width="0" height="14" rx="7" fill="url(#bts)" filter="url(#barg)"><animate attributeName="width" from="0" to="468" dur="1.4s" fill="freeze" begin="0.9s"/></rect>
  <rect x="120" y="220" width="0" height="14" rx="7" fill="url(#bts)"><animate attributeName="width" from="0" to="468" dur="1.4s" fill="freeze" begin="0.9s"/></rect>
  <text x="855" y="232" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#3178C6" text-anchor="end">65%</text>

  <text x="30" y="272" font-family="'Segoe UI',Arial,sans-serif" font-size="12" fill="#64748b">Node.js</text>
  <rect x="120" y="260" width="720" height="14" rx="7" fill="#1e293b"/>
  <rect x="120" y="260" width="0" height="14" rx="7" fill="url(#bn)" filter="url(#barg)"><animate attributeName="width" from="0" to="432" dur="1.4s" fill="freeze" begin="1.1s"/></rect>
  <rect x="120" y="260" width="0" height="14" rx="7" fill="url(#bn)"><animate attributeName="width" from="0" to="432" dur="1.4s" fill="freeze" begin="1.1s"/></rect>
  <text x="855" y="272" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#339933" text-anchor="end">60%</text>
</svg>

<br/><br/>

<svg width="900" height="155" viewBox="0 0 900 155" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="gridbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="100%" style="stop-color:#0d1f3c"/>
    </linearGradient>
  </defs>
  <rect width="900" height="155" rx="14" fill="url(#gridbg)" stroke="#1e293b" stroke-width="1"/>
  <text x="30" y="30" font-family="'Segoe UI',Arial,sans-serif" font-size="13" font-weight="600" fill="#e2e8f0" letter-spacing="2">CONTRIBUTION ACTIVITY  ·  2023 – 2026</text>

  <text x="30" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Jul 23</text>
  <text x="140" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Oct</text>
  <text x="240" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Jan 24</text>
  <text x="350" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Apr</text>
  <text x="450" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Jul</text>
  <text x="560" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Oct</text>
  <text x="660" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Jan 25</text>
  <text x="770" y="52" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Now</text>

  <g fill="#0e4429">
    <rect x="28" y="58" width="10" height="10" rx="2"/><rect x="28" y="71" width="10" height="10" rx="2"/><rect x="42" y="84" width="10" height="10" rx="2"/><rect x="56" y="58" width="10" height="10" rx="2"/><rect x="84" y="71" width="10" height="10" rx="2"/><rect x="98" y="58" width="10" height="10" rx="2"/><rect x="112" y="84" width="10" height="10" rx="2"/><rect x="126" y="71" width="10" height="10" rx="2"/><rect x="154" y="58" width="10" height="10" rx="2"/><rect x="168" y="84" width="10" height="10" rx="2"/><rect x="182" y="71" width="10" height="10" rx="2"/><rect x="210" y="58" width="10" height="10" rx="2"/><rect x="224" y="84" width="10" height="10" rx="2"/><rect x="252" y="71" width="10" height="10" rx="2"/><rect x="266" y="58" width="10" height="10" rx="2"/><rect x="294" y="84" width="10" height="10" rx="2"/><rect x="308" y="58" width="10" height="10" rx="2"/><rect x="336" y="71" width="10" height="10" rx="2"/><rect x="364" y="84" width="10" height="10" rx="2"/><rect x="392" y="58" width="10" height="10" rx="2"/><rect x="406" y="71" width="10" height="10" rx="2"/><rect x="434" y="58" width="10" height="10" rx="2"/><rect x="448" y="84" width="10" height="10" rx="2"/><rect x="476" y="71" width="10" height="10" rx="2"/><rect x="504" y="58" width="10" height="10" rx="2"/><rect x="518" y="84" width="10" height="10" rx="2"/><rect x="546" y="71" width="10" height="10" rx="2"/><rect x="574" y="58" width="10" height="10" rx="2"/><rect x="588" y="84" width="10" height="10" rx="2"/><rect x="616" y="71" width="10" height="10" rx="2"/><rect x="630" y="58" width="10" height="10" rx="2"/><rect x="672" y="84" width="10" height="10" rx="2"/><rect x="700" y="71" width="10" height="10" rx="2"/><rect x="728" y="58" width="10" height="10" rx="2"/><rect x="756" y="84" width="10" height="10" rx="2"/><rect x="784" y="71" width="10" height="10" rx="2"/><rect x="812" y="58" width="10" height="10" rx="2"/><rect x="840" y="84" width="10" height="10" rx="2"/><rect x="868" y="71" width="10" height="10" rx="2"/>
  </g>
  <g fill="#006d32">
    <rect x="42" y="58" width="10" height="10" rx="2"/><rect x="56" y="71" width="10" height="10" rx="2"/><rect x="70" y="84" width="10" height="10" rx="2"/><rect x="98" y="71" width="10" height="10" rx="2"/><rect x="126" y="84" width="10" height="10" rx="2"/><rect x="140" y="58" width="10" height="10" rx="2"/><rect x="168" y="71" width="10" height="10" rx="2"/><rect x="196" y="84" width="10" height="10" rx="2"/><rect x="238" y="71" width="10" height="10" rx="2"/><rect x="280" y="84" width="10" height="10" rx="2"/><rect x="322" y="58" width="10" height="10" rx="2"/><rect x="350" y="71" width="10" height="10" rx="2"/><rect x="378" y="84" width="10" height="10" rx="2"/><rect x="420" y="71" width="10" height="10" rx="2"/><rect x="462" y="84" width="10" height="10" rx="2"/><rect x="490" y="58" width="10" height="10" rx="2"/><rect x="532" y="71" width="10" height="10" rx="2"/><rect x="560" y="84" width="10" height="10" rx="2"/><rect x="602" y="58" width="10" height="10" rx="2"/><rect x="644" y="71" width="10" height="10" rx="2"/><rect x="686" y="58" width="10" height="10" rx="2"/><rect x="714" y="84" width="10" height="10" rx="2"/><rect x="742" y="71" width="10" height="10" rx="2"/><rect x="770" y="58" width="10" height="10" rx="2"/><rect x="798" y="84" width="10" height="10" rx="2"/><rect x="826" y="58" width="10" height="10" rx="2"/><rect x="854" y="71" width="10" height="10" rx="2"/>
  </g>
  <g fill="#26a641">
    <rect x="70" y="58" width="10" height="10" rx="2"/><rect x="112" y="58" width="10" height="10" rx="2"/><rect x="196" y="58" width="10" height="10" rx="2"/><rect x="266" y="71" width="10" height="10" rx="2"/><rect x="336" y="84" width="10" height="10" rx="2"/><rect x="462" y="58" width="10" height="10" rx="2"/><rect x="560" y="58" width="10" height="10" rx="2"/><rect x="658" y="84" width="10" height="10" rx="2"/><rect x="770" y="71" width="10" height="10" rx="2"/>
  </g>
  <g fill="#39d353">
    <rect x="322" y="71" width="10" height="10" rx="2"><animate attributeName="opacity" values="1;0.4;1" dur="2.2s" repeatCount="indefinite"/></rect>
    <rect x="868" y="58" width="10" height="10" rx="2"><animate attributeName="opacity" values="1;0.3;1" dur="1.7s" repeatCount="indefinite"/></rect>
    <rect x="854" y="84" width="10" height="10" rx="2"><animate attributeName="opacity" values="0.6;1;0.6" dur="2.8s" repeatCount="indefinite"/></rect>
  </g>

  <text x="30" y="140" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">Less</text>
  <rect x="58" y="130" width="10" height="10" rx="2" fill="#161b22" stroke="#30363d" stroke-width="0.5"/>
  <rect x="72" y="130" width="10" height="10" rx="2" fill="#0e4429"/>
  <rect x="86" y="130" width="10" height="10" rx="2" fill="#006d32"/>
  <rect x="100" y="130" width="10" height="10" rx="2" fill="#26a641"/>
  <rect x="114" y="130" width="10" height="10" rx="2" fill="#39d353"/>
  <text x="128" y="140" font-family="'Segoe UI',Arial,sans-serif" font-size="9" fill="#334155">More</text>
</svg>

</div>

---

<div align="center">

<svg width="900" height="56" viewBox="0 0 900 56" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="secbg6" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#0d1117"/>
      <stop offset="50%" style="stop-color:#0d1f3c"/>
      <stop offset="100%" style="stop-color:#0d1117"/>
    </linearGradient>
    <linearGradient id="lg6" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="25%" style="stop-color:#00d9ff"/>
      <stop offset="75%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
  </defs>
  <rect width="900" height="56" fill="url(#secbg6)" rx="10"/>
  <rect x="1" y="1" width="898" height="54" fill="none" stroke="url(#lg6)" stroke-width="0.5" rx="10" opacity="0.4"/>
  <text x="450" y="35" font-family="'Segoe UI',Arial,sans-serif" font-size="15" font-weight="600" fill="#e2e8f0" text-anchor="middle" letter-spacing="4">◈  CONNECT WITH ME  ◈</text>
</svg>

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-SivaPrasannaS-0d1117?style=for-the-badge&logo=github&logoColor=ffffff&labelColor=161b22)](https://github.com/SivaPrasannaS)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Siva_Prasanna_S-0d1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2&labelColor=161b22)](https://www.linkedin.com/in/siva-prasanna-4725b6171)
[![Credly](https://img.shields.io/badge/Credly-Badges-0d1117?style=for-the-badge&logo=credly&logoColor=FF6B00&labelColor=161b22)](https://www.credly.com/users/siva-prasanna-s.b75f15a3)
[![Email](https://img.shields.io/badge/Email-Say_Hello-0d1117?style=for-the-badge&logo=gmail&logoColor=EA4335&labelColor=161b22)](mailto:your.email@example.com)

<br/>

<svg width="900" height="90" viewBox="0 0 900 90" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footbg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#020818">
        <animate attributeName="stop-color" values="#020818;#0a1628;#020818" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#0d1f3c">
        <animate attributeName="stop-color" values="#0d1f3c;#1a3a6e;#0d1f3c" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
    <linearGradient id="footline" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#00fff2;stop-opacity:0"/>
      <stop offset="30%" style="stop-color:#00d9ff"/>
      <stop offset="70%" style="stop-color:#7b61ff"/>
      <stop offset="100%" style="stop-color:#ff61d8;stop-opacity:0"/>
    </linearGradient>
    <filter id="qg">
      <feGaussianBlur stdDeviation="2" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  <rect width="900" height="90" rx="14" fill="url(#footbg)" stroke="#1e293b" stroke-width="1"/>
  <rect x="0" y="0" width="900" height="3" rx="1" fill="url(#footline)">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="0" width="900" height="3" rx="1" fill="url(#footline)" filter="url(#qg)" opacity="0.6">
    <animate attributeName="opacity" values="0.3;0.7;0.3" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="450" y="46" font-family="'Segoe UI',Arial,sans-serif" font-size="13" fill="#94a3b8" text-anchor="middle" font-style="italic">"First, solve the problem. Then, write the code."</text>
  <text x="450" y="68" font-family="'Segoe UI',Arial,sans-serif" font-size="11" fill="#475569" text-anchor="middle">— John Johnson</text>
</svg>

</div>
