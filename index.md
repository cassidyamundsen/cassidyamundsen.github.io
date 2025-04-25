---
layout: single
excerpt: "Linguist | NLP Enthusiast | Data Analyst | Sales Professional"
classes: wide
---

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<style>
  :root {
    --accent-color: #457b9d;
    --accent-hover: #1d3557;
    --text-dark: #1a1a1a;
    --text-medium: #4a4a4a;
    --bg-main: #f7f9fb;
    --bg-card: #ffffff;
    --header-bg: #457b9d;
    --footer-bg: #457b9d;
  }

  body,
  .page,
  .page__wrapper,
  .layout--single {
    margin: 0 auto !important;
    max-width: 1200px;
    padding: 0 1rem;
  }

  body {
    font-family: 'Poppins', sans-serif;
    background-color: var(--bg-main);
    color: var(--text-dark);
    padding-bottom: 80px;
  }

  h1, h2, h3 {
    color: var(--accent-color);
    font-weight: 600;
  }

  p {
    font-size: 1.1rem;
    color: var(--text-medium);
  }

  a {
    color: var(--accent-color);
    text-decoration: none;
  }

  a:hover {
    color: var(--accent-hover);
    text-decoration: underline;
  }

  .intro-card {
    padding: 2rem;
    max-width: 700px;
    margin: 4rem auto;
    background: var(--bg-card);
    border-radius: 16px;
    box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
    text-align: center;
  }

  .intro-button {
    margin-top: 1.5rem;
    padding: 0.75rem 1.5rem;
    background-color: var(--accent-color);
    color: #ffffff !important;
    border: none;
    border-radius: 8px;
    font-size: 1rem;
    cursor: pointer;
    transition: background 0.3s ease;
    text-decoration: none;
    display: inline-block;
  }

  .intro-button:hover {
    background-color: var(--accent-hover);
  }

  header.site-header {
    background-color: var(--header-bg) !important;
    color: #ffffff !important;
    border-bottom: none !important;
  }

  footer.page__footer {
    background-color: var(--footer-bg) !important;
    color: #ffffff !important;
    border-top: none !important;
    text-align: center;
  }

  footer.page__footer .page__footer-follow,
  footer.page__footer .page__footer-copyright,
  footer.page__footer .page__footer-links a[href*="feed.xml"] {
    display: none !important;
  }

  .contact-toggle {
    margin: 3rem auto;
    text-align: center;
  }

  .contact-toggle button {
    background-color: var(--accent-color);
    color: #ffffff;
    font-size: 1rem;
    padding: 0.75rem 1.5rem;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: background 0.3s ease;
  }

  .contact-toggle button:hover {
    background-color: var(--accent-hover);
  }

  .contact-info {
    margin-top: 1rem;
    display: none;
    color: var(--text-medium);
    font-size: 1.05rem;
  }
</style>

<div class="intro-card">
  <h1>Hi, I'm Cassidy</h1>
  <p>I'm a linguist, data analyst, and sales professional who studies how people communicate—then turns those insights into strategies that connect, convert, and make an impact. I combine research, empathy, and analytics to bridge the gap between language and business.</p>
  <a class="intro-button" href="/about/">Learn More About Me</a>
</div>

<div class="contact-toggle">
  <button onclick="document.getElementById('contact').style.display = 'block'">Show Contact Info</button>
  <div id="contact" class="contact-info">
    <p>Email: <a href="mailto:amundsen.cassidy@gmail.com">amundsen.cassidy@gmail.com</a></p>
    <p>GitHub: <a href="https://github.com/cassidyamundsen" target="_blank">github.com/cassidyamundsen</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/cassidyamundsen" target="_blank">linkedin.com/in/cassidyamundsen</a></p>
  </div>
</div>
