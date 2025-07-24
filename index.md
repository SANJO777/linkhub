---
layout: none
title: ""
---

<style>
  :root {
    --bg-light: #f7f0ff;
    --text-light: #3d0066;
    --accent-light: #b57fff;

    --bg-dark: #1a0b24;
    --text-dark: #e7dbff;
    --accent-dark: #d5aaff;
  }

  body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 20px;
    transition: background 0.3s, color 0.3s;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    overflow: hidden;
  }

  @media (prefers-color-scheme: light) {
    body { background: var(--bg-light); color: var(--text-light); }
    a { color: var(--accent-light); }
  }

  @media (prefers-color-scheme: dark) {
    body { background: var(--bg-dark); color: var(--text-dark); }
    a { color: var(--accent-dark); }
  }

  .link-box {
    background-color: var(--bg-light);
    color: var(--text-light);
    padding: 30px 20px;
    border-radius: 16px;
    box-shadow: 0 0 16px rgba(0, 0, 0, 0.1);
    text-align: center;
    width: 100%;
    max-width: 400px;
    transition: all 0.3s ease;
  }

  @media (prefers-color-scheme: dark) {
    .link-box {
      background-color: var(--bg-dark);
      color: var(--text-dark);
      box-shadow: 0 0 16px rgba(255, 255, 255, 0.05);
    }
  }

  .link-box h2 {
    margin-bottom: 20px;
    font-size: 1.6rem;
    position: relative;
    animation: glow 2s ease-in-out infinite alternate;
  }

  @keyframes glow {
    0% { text-shadow: 0 0 4px var(--accent-light); }
    100% { text-shadow: 0 0 14px var(--accent-light); }
  }

  @media (prefers-color-scheme: dark) {
    @keyframes glow {
      0% { text-shadow: 0 0 4px var(--accent-dark); }
      100% { text-shadow: 0 0 14px var(--accent-dark); }
    }
  }

  .social-link {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    gap: 12px;
    background-color: var(--accent-light);
    color: white;
    text-decoration: none;
    padding: 12px 16px;
    margin: 10px 0;
    border-radius: 12px;
    font-weight: bold;
    box-shadow: 0 0 6px rgba(0, 0, 0, 0.1);
    transition: background 0.3s, transform 0.3s, box-shadow 0.3s;
    opacity: 0;
    transform: translateY(20px);
    animation: slideIn 0.6s forwards;
  }

  .social-link img {
    width: 20px;
    height: 20px;
  }

  .social-link:nth-of-type(1) { animation-delay: 0.3s; }
  .social-link:nth-of-type(2) { animation-delay: 0.45s; }
  .social-link:nth-of-type(3) { animation-delay: 0.6s; }
  .social-link:nth-of-type(4) { animation-delay: 0.75s; }
  .social-link:nth-of-type(5) { animation-delay: 0.9s; }

  @keyframes slideIn {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .social-link:hover {
    background-color: var(--text-light);
    transform: scale(1.06);
    box-shadow: 0 0 16px var(--accent-light);
  }

  @media (prefers-color-scheme: dark) {
    .social-link {
      background-color: var(--accent-dark);
    }

    .social-link:hover {
      background-color: var(--text-dark);
      color: var(--bg-dark);
      box-shadow: 0 0 16px var(--accent-dark);
    }
  }

  .profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 4px solid var(--accent-light);
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    transition: transform 0.2s;
  }

  .profile-pic:hover {
    transform: scale(1.05);
  }

  @media (prefers-color-scheme: dark) {
    .profile-pic {
      border-color: var(--accent-dark);
    }
  }
</style>

<div class="link-box">
  <a href="https://github.com/SANJO777" target="_blank">
    <img src="https://github.com/SANJO777.png" alt="Santiago Rodríguez" class="profile-pic">
  </a>
  <h2>My Social Links</h2>

  <a class="social-link" href="https://github.com/SANJO777" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111432.png" alt="GitHub Icon"> GitHub
  </a>

  <a class="social-link" href="https://sanjo777.github.io/portfolio/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/841/841364.png" alt="Portfolio Icon"> Portfolio
  </a>

  <a class="social-link" href="https://www.linkedin.com/in/santiago-rodr%C3%ADguez-0b7476375/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn Icon"> LinkedIn
  </a>

  <a class="social-link" href="https://instagram.com/saantiago.rodriguez/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram Icon"> Instagram
  </a>

  <a class="social-link" href="https://www.youtube.com/@sjrpnocommentary" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="YouTube Icon"> YouTube
  </a>
</div>
