<!-- Guarda este archivo como banner.svg y súbelo a tu repositorio -->
<!-- GitHub SÍ soporta animaciones SVG en README -->

<svg width="1200" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Fondo animado -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0a1d37">
        <animate attributeName="stop-color" values="#0a1d37;#001f3f;#0a1d37" dur="6s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#001f3f">
        <animate attributeName="stop-color" values="#001f3f;#0a1d37;#001f3f" dur="6s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <!-- Brillo texto -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur" />
      <feMerge>
        <feMergeNode in="coloredBlur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
  </defs>

  <!-- Fondo -->
  <rect width="1200" height="300" fill="url(#bg)" rx="20" />

  <!-- Olas -->
  <path d="M0 220 Q 150 200 300 220 T 600 220 T 900 220 T 1200 220 V300 H0 Z" fill="rgba(255,255,255,0.08)">
    <animateTransform attributeName="transform" type="translate" from="0 0" to="-200 0" dur="6s" repeatCount="indefinite" />
  </path>

  <path d="M0 240 Q 150 260 300 240 T 600 240 T 900 240 T 1200 240 V300 H0 Z" fill="rgba(255,255,255,0.05)">
    <animateTransform attributeName="transform" type="translate" from="0 0" to="200 0" dur="10s" repeatCount="indefinite" />
  </path>

  <!-- Emoji pirata -->
  <text x="60" y="80" font-size="48">🏴‍☠️
    <animateTransform attributeName="transform" type="translate" from="0 0" to="0 -10" dur="2s" repeatCount="indefinite" direction="alternate" />
  </text>

  <!-- Texto principal -->
  <text x="600" y="150" text-anchor="middle" font-size="56" fill="#ffcc00" filter="url(#glow)" font-family="Verdana, sans-serif">
    ONE PIECE DEVELOPER
    <animate attributeName="opacity" values="1;0.8;1" dur="2s" repeatCount="indefinite" />
  </text>

  <!-- Subtítulo -->
  <text x="600" y="195" text-anchor="middle" font-size="22" fill="#ffffff" font-family="Verdana, sans-serif" opacity="0.9">
    Becoming a great developer, one commit at a time
  </text>
</svg>


# 👋 Hola, soy Kevin Perez



💻 Estudiante de desarrollo de software en Colombia.


### 🚀 Tecnologías que estoy aprendiendo
- HTML
- SQL
- Javascript
- Lógica de programación
- Git & GitHub

![PSeInt](https://img.shields.io/badge/PSeInt-purple?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)


### 📂 Proyectos destacados
- 📊 Bases de datos académicas
- 🎮 Juegos de lógica en consola
- Calculadoras
- Analisis de datos / movilidad en bogota


### 🎯 Objetivo
Seguir mejorando mis habilidades para trabajar como desarrollador y participar en proyectos reales.


---
⭐ Siempre aprendiendo
