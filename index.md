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
  }

  .social-link {
    display: block;
    background-color: var(--accent-light);
    color: white;
    text-decoration: none;
    padding: 12px;
    margin: 10px 0;
    border-radius: 12px;
    font-weight: bold;
    transition: background 0.3s, transform 0.2s;
  }

  .social-link:hover {
    background-color: var(--text-light);
    transform: scale(1.03);
  }

  @media (prefers-color-scheme: dark) {
    .social-link {
      background-color: var(--accent-dark);
    }

    .social-link:hover {
      background-color: var(--text-dark);
    }
  }

  .profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 4px solid var(--accent-light);
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }

  @media (prefers-color-scheme: dark) {
    .profile-pic {
      border-color: var(--accent-dark);
    }
  }
</style>

<div class="link-box">
  <img src="https://github.com/SANJO777.png" alt="Santiago Rodríguez" class="profile-pic">
  <h2>My Social Links</h2>
  <a class="social-link" href="https://github.com/SANJO777" target="_blank">GitHub</a>
  <a class="social-link" href="https://sanjo777.github.io/portfolio/" target="_blank">Portfolio</a>
  <a class="social-link" href="https://www.linkedin.com/in/santiago-rodr%C3%ADguez-0b7476375/" target="_blank">LinkedIn</a>
  <a class="social-link" href="https://instagram.com/saantiago.rodriguez/" target="_blank">Instagram</a>
  <a class="social-link" href="https://www.youtube.com/@sjrpnocommentary" target="_blank">YouTube</a>
</div>