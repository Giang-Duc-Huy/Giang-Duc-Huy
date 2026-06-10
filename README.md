<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Huy – Fullstack Developer</title>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@tabler/icons-webfont@3.19.0/dist/tabler-icons.min.css"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: system-ui, sans-serif; background: #fff; color: #111; padding: 2rem 1rem; }
  .profile-wrap { max-width: 680px; margin: 0 auto; }
  .center { text-align: center; }
  .divider { border: none; border-top: 0.5px solid #e0e0e0; margin: 1.5rem 0; }
  .section-title { font-size: 15px; font-weight: 500; margin: 0 0 12px; color: #666; }
  .badge-grid { display: flex; flex-wrap: wrap; gap: 8px; }
  .badge { display: inline-flex; align-items: center; gap: 6px; padding: 5px 10px; border-radius: 8px; font-size: 12px; font-weight: 500; border: 0.5px solid #ddd; background: #f5f5f5; color: #111; }
  .about-list { list-style: none; display: flex; flex-direction: column; gap: 6px; }
  .about-list li { font-size: 14px; color: #555; display: flex; align-items: center; gap: 8px; }
  .about-list li::before { content: '▸'; color: #aaa; }
  .social-row { display: flex; gap: 10px; justify-content: center; }
  .social-btn { display: inline-flex; align-items: center; gap: 6px; padding: 6px 14px; border-radius: 8px; font-size: 13px; font-weight: 500; border: 0.5px solid #ccc; background: #f5f5f5; color: #111; text-decoration: none; }
  .social-btn:hover { background: #eee; }
  .focus-cards { display: grid; grid-template-columns: repeat(auto-fit, minmax(150px, 1fr)); gap: 10px; }
  .focus-card { background: #f5f5f5; border-radius: 8px; padding: 12px 14px; border: 0.5px solid #ddd; font-size: 13px; color: #555; display: flex; align-items: center; gap: 8px; }
  .name-title { font-size: 26px; font-weight: 500; margin: 0 0 4px; }
  .sub-title { font-size: 14px; color: #666; margin: 0 0 6px; }
  .desc { font-size: 13px; color: #999; margin: 0; }
  .avatar { width: 64px; height: 64px; border-radius: 50%; background: #e6f1fb; display: flex; align-items: center; justify-content: center; font-size: 22px; font-weight: 500; color: #185fa5; margin: 0 auto 12px; border: 0.5px solid #ddd; }
</style>
</head>
<body>
<div class="profile-wrap">
  <div class="center">
    <div class="avatar">H</div>
    <p class="name-title">Hi 👋, I'm Huy</p>
    <p class="sub-title">Fullstack Developer · UI/UX Enthusiast</p>
    <p class="desc">I design &amp; build modern web applications from UI to backend systems</p>
  </div>

  <hr class="divider"/>

  <p class="section-title">About me</p>
  <ul class="about-list">
    <li>Developer from Vietnam 🇻🇳</li>
    <li>Fullstack with React, Node.js, .NET</li>
    <li>Interested in UI/UX &amp; Product Design</li>
  </ul>

  <hr class="divider"/>

  <p class="section-title">Languages</p>
  <div class="badge-grid">

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#F7DF1E"/><path d="M6 26.5l3.1-1.9c.6 1.1 1.1 2 2.4 2 1.2 0 2-.5 2-2.3V12h3.8v12.4c0 3.8-2.2 5.5-5.5 5.5-2.9 0-4.6-1.5-5.8-3.4zm13.3-.4l3.1-1.8c.8 1.3 1.8 2.3 3.7 2.3 1.5 0 2.5-.8 2.5-1.8 0-1.3-.9-1.7-2.7-2.5l-.9-.4c-2.8-1.2-4.6-2.7-4.6-5.8 0-2.9 2.2-5 5.6-5 2.4 0 4.2.8 5.4 3l-2.9 1.9c-.7-1.2-1.4-1.6-2.5-1.6-1.1 0-1.8.7-1.8 1.6 0 1.1.7 1.6 2.4 2.3l.9.4c3.2 1.4 5 2.8 5 6 0 3.4-2.7 5.3-6.3 5.3-3.5 0-5.8-1.7-6.9-3.9z" fill="#333"/></svg>
      JavaScript
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#239120"/><text x="16" y="22" font-size="12" font-weight="700" text-anchor="middle" fill="#fff">C#</text></svg>
      C#
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#3776AB"/><path d="M15.9 6C10.4 6 10.7 8.4 10.7 8.4L10.7 10.9H16V11.7H8.5C8.5 11.7 5 11.3 5 16.9s3 5 3 5h1.8v-2.6s-.1-3 2.9-3h5c0 0 2.8.05 2.8-2.7V9.1S21 6 15.9 6zM13 7.8c.5 0 .9.4.9.9s-.4.9-.9.9-.9-.4-.9-.9.4-.9.9-.9z" fill="#fff"/><path d="M16.1 26C21.6 26 21.3 23.6 21.3 23.6L21.3 21.1H16V20.3H23.5C23.5 20.3 27 20.7 27 15.1s-3-5-3-5h-1.8v2.6s.1 3-2.9 3h-5c0 0-2.8-.05-2.8 2.7V22.9S11 26 16.1 26zM19 24.2c-.5 0-.9-.4-.9-.9s.4-.9.9-.9.9.4.9.9-.4.9-.9.9z" fill="#FFD43B"/></svg>
      Python
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#E34F26"/><path d="M6 28l-2-22h24l-2 22-10 3-10-3z" fill="#E34F26"/><path d="M16 27.5l8.1-2.2 1.7-19.3H16v21.5z" fill="#EF652A"/><path d="M16 14h4.3l.3-3.5H16V7H24l-.1.9-1 11.1H16v-5z" fill="#fff"/><path d="M16 22.4l-.05.02-3.6-1-.23-2.6H9.4l.46 5.2 6.11 1.7.03-.01v-3.31z" fill="#EBEBEB"/><path d="M16 14v3h-4l-.28-3H16zM16 7v3.5h-6.4L9.4 7H16z" fill="#fff"/></svg>
      HTML5
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#1572B6"/><path d="M6 28l-2-22h24l-2 22-10 3-10-3z" fill="#1572B6"/><path d="M16 27.5l8.1-2.2 1.7-19.3H16v21.5z" fill="#33A9DC"/><path d="M16 14h4.1l.4-4H16V7h8l-.1.9-1 10.1H16v-4zM16 22.6l-.05.02-3.8-1-.24-2.6H9.4l.46 5.2 6.1 1.7.04-.01v-3.31z" fill="#fff"/><path d="M16 14v4h-3.8l-.27-4H16zM16 7v3H9.6L9.4 7H16z" fill="#EBEBEB"/></svg>
      CSS3
    </span>
  </div>

  <hr class="divider"/>

  <p class="section-title">Frameworks &amp; tools</p>
  <div class="badge-grid">

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#20232A"/><circle cx="16" cy="16" r="3" fill="#61DAFB"/><ellipse cx="16" cy="16" rx="12" ry="4.5" stroke="#61DAFB" stroke-width="1.5" fill="none"/><ellipse cx="16" cy="16" rx="12" ry="4.5" stroke="#61DAFB" stroke-width="1.5" fill="none" transform="rotate(60 16 16)"/><ellipse cx="16" cy="16" rx="12" ry="4.5" stroke="#61DAFB" stroke-width="1.5" fill="none" transform="rotate(120 16 16)"/></svg>
      React
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#333"/><path d="M5 22.5l3-13.5h2.5l-3 13.5H5zm7.5 0l1.5-7-1-6.5h2.5l.5 4.5 2.5-4.5H21l-4.5 7.5-1 6H12.5zm10 0l.5-6-3-7.5h2.5l2 5 1-5H27l-2 7.5-.5 6H22.5z" fill="#83CD29"/></svg>
      Node.js
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#512BD4"/><path d="M8 8h16v2.5H8V8zm0 6.75h16v2.5H8v-2.5zm0 6.75h8v2.5H8v-2.5z" fill="#fff"/></svg>
      .NET
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#06B6D4"/><path d="M4 21a2 2 0 100-4 2 2 0 000 4zm24 0a2 2 0 100-4 2 2 0 000 4zm-12 6a2 2 0 100-4 2 2 0 000 4z" fill="#fff"/><path d="M7 19h4M25 19h-4M16 25v-4M7 19c2-4 5-6 9-6s7 2 9 6" stroke="#fff" stroke-width="1.5" stroke-linecap="round" fill="none"/></svg>
      Tailwind CSS
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#F24E1E"/><rect x="6" y="6" width="8" height="8" rx="1" fill="#fff"/><rect x="18" y="6" width="8" height="8" rx="1" fill="#A259FF"/><rect x="6" y="18" width="8" height="8" rx="1" fill="#0ACF83"/><rect x="18" y="18" width="8" height="8" rx="4" fill="#1ABCFE"/></svg>
      Figma
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#F05032"/><path d="M27 14.8l-9.8-9.8a1.7 1.7 0 00-2.4 0L12.4 7.4l3 3a2 2 0 012.5 2.5l2.9 2.9a2 2 0 11-1.2 1.2l-2.7-2.7v7a2 2 0 11-1.6 0v-7a2 2 0 01-1.1-2.6L11.2 9 5 15.2a1.7 1.7 0 000 2.4l9.8 9.8a1.7 1.7 0 002.4 0L27 17.2a1.7 1.7 0 000-2.4z" fill="#fff"/></svg>
      Git
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#E87D0D"/><path d="M6 22l4-12h2l2 6 2-6h2l4 12h-2l-3-8-2 6h-2l-2-6-3 8H6z" fill="#fff"/></svg>
      Blender
    </span>
  </div>

  <hr class="divider"/>

  <p class="section-title">Database &amp; backend</p>
  <div class="badge-grid">

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#316192"/><ellipse cx="16" cy="9" rx="9" ry="3.5" fill="#fff" opacity=".9"/><path d="M7 9v6c0 1.9 4 3.5 9 3.5s9-1.6 9-3.5V9" stroke="#fff" stroke-width="1.5" fill="none"/><path d="M7 15v6c0 1.9 4 3.5 9 3.5s9-1.6 9-3.5v-6" stroke="#fff" stroke-width="1.5" fill="none"/></svg>
      PostgreSQL
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#47A248"/><path d="M16 5c-3.3 5-5 9-5 12a5 5 0 0010 0c0-3-1.7-7-5-12z" fill="#fff" opacity=".9"/><path d="M10 13c-3 1-5 3-5 5a5 5 0 008.7 3.4" stroke="#fff" stroke-width="1.5" stroke-linecap="round" fill="none"/><path d="M22 13c3 1 5 3 5 5a5 5 0 01-8.7 3.4" stroke="#fff" stroke-width="1.5" stroke-linecap="round" fill="none"/></svg>
      MongoDB
    </span>

    <span class="badge">
      <svg width="16" height="16" viewBox="0 0 32 32" fill="none"><rect width="32" height="32" rx="4" fill="#333"/><path d="M6 20l3-3h4l2-2v-4l3-3 3 3v4l2 2h4l3 3-3 3h-4l-2 2v2l-3 1-3-1v-2l-2-2H9l-3-3z" stroke="#fff" stroke-width="1.3" fill="none" stroke-linejoin="round"/></svg>
      REST API
    </span>
  </div>

  <hr class="divider"/>

  <p class="section-title">Current focus</p>
  <div class="focus-cards">
    <div class="focus-card"><i class="ti ti-code" style="font-size:18px; color:#185fa5;"></i> Fullstack Web Dev</div>
    <div class="focus-card"><i class="ti ti-vector-pen" style="font-size:18px; color:#0f6e56;"></i> UI/UX with Figma</div>
    <div class="focus-card"><i class="ti ti-server" style="font-size:18px; color:#854f0b;"></i> Scalable Backend</div>
  </div>

  <hr class="divider"/>

  <p class="section-title" style="text-align:center">Connect with me</p>
  <div class="social-row">
    <a class="social-btn" href="https://github.com/Giang-Duc-Huy" target="_blank"><i class="ti ti-brand-github" style="font-size:16px"></i> GitHub</a>
    <a class="social-btn" href="https://www.facebook.com/cancel.giang" target="_blank"><i class="ti ti-brand-facebook" style="font-size:16px"></i> Facebook</a>
    <a class="social-btn" href="https://www.linkedin.com/in/hijang17/" target="_blank"><i class="ti ti-brand-linkedin" style="font-size:16px"></i> LinkedIn</a>
  </div>
</div>
</body>
</html>
