---
layout: single
title: "Cassidy Amundsen"
excerpt: "Linguist | NLP Enthusiast | Data Analyst"
classes: wide
---

<!-- Modern Font and Style Imports -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

<style>
  body {
    font-family: 'Poppins', sans-serif;
    background-color: #0e1117;
    color: #f5f5f5;
    margin: 0;
    padding-bottom: 80px;
  }
  h1, h2, h3 {
    color: #ffffff;
    font-weight: 600;
  }
  p {
    font-size: 1.1rem;
    color: #c9d1d9;
  }
  a {
    color: #58a6ff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  .intro-card {
    padding: 2rem;
    max-width: 700px;
    margin: 4rem auto;
    background: #161b22;
    border-radius: 16px;
    box-shadow: 0 4px 16px rgba(255, 255, 255, 0.05);
    text-align: center;
  }
  .intro-button {
    margin-top: 1.5rem;
    padding: 0.75rem 1.5rem;
    background-color: #238636;
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
    background-color: #2ea043;
  }
  .connect {
    text-align: center;
    margin: 4rem auto 2rem;
  }
  .connect h2 {
    font-size: 1.6rem;
    margin-bottom: 1rem;
  }
  .social-icons {
    display: flex;
    justify-content: center;
    gap: 1.5rem;
    font-size: 1.8rem;
    margin-top: 0.5rem;
  }
  .social-icons a {
    color: #58a6ff;
  }
  .footer {
    position: fixed;
    bottom: 0;
    width: 100%;
    background-color: #0d1117;
    text-align: center;
    padding: 1rem 0;
    font-size: 0.9rem;
    color: #8b949e;
  }
</style>

<div class="intro-card">
  <h1>Hi, I'm Cassidy 👋</h1>
  <p>I'm a linguist and data analyst passionate about how people use language — and how we can use technology and data to better understand and connect with each other.</p>
  <a class="intro-button" href="/about/">Learn More About Me</a>
</div>

<div class="connect">
  <h2>Let’s Connect</h2>
  <div class="social-icons">
    <a href="https://github.com/cassidyamundsen" target="_blank" title="GitHub"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/cassidyamundsen" target="_blank" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
    <a href="mailto:amundsen.cassidy@gmail.com" title="Email"><i class="fas fa-envelope"></i></a>
  </div>
</div>

<div class="footer">
  © 2025 Cassidy Amundsen · Made with ❤️ and Python
</div>

<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
<script>
  // Easter egg: click the footer 5 times
  let clickCount = 0;
  document.querySelector('.footer').addEventListener('click', () => {
    clickCount++;
    if (clickCount === 5) {
      alert("🍸 You've unlocked the secret cocktail: The Linguist — gin, lavender syrup, lemon juice, shaken not stirred.");
      clickCount = 0;
    }
  });
</script>
