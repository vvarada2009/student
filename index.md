---
layout: base
title: I'm Varada Chirag Vichare
hide: true
---

### Me and Team

Hi! My name is  🍩Varada Chirag Vichare 🍩.

| Role         | Name     | Repo Location                       | Stream                | Repo Name |
|--------------|----------|-------------------------------------|-----------------------|-----------|
| Scrum Master | John     | github.com/jm1021/student           | upstream (OCS fork)   | student   |
| Scrummer     | Torin    | github.com/torin/student            | downstream (fork)     | student   |
| Scrummer     | Avantika | github.com/avantika/student         | downstream (fork)     | student   |
| Scrummer     | Aadit    | github.com/aaadit/student           | downstream (fork)     | student   |

## Links to Learning

### Development Environment

> Coding starts with tools, explore these tools and procedures with a click.

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="https://github.com/Open-Coding-Society/student">
        <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
    </a>
    <a href="https://open-coding-society.github.io/student">
        <img src="https://img.shields.io/badge/GitHub%20Pages-327FC7?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages">
    </a>
    <a href="https://kasm.nighthawkcodingsociety.com/">
        <img src="https://img.shields.io/badge/KASM-0078D4?style=for-the-badge&logo=kasm&logoColor=white" alt="KASM">
    </a>
    <a href="https://vscode.dev/">
        <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VSCode">
    </a>
</div>

<br>

### Class Progress

> Here is my progress through coding, click to see these online

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <a href="{{site.baseurl}}/snake" style="text-decoration: none;">
        <div style="background-color: #ff0000ff; color: black; padding: 10px 20px; border-radius: 5px; font-weight: bold;">
            Snake Game
        </div>
    </a>
    <a href="{{site.baseurl}}/turtle" style="text-decoration: none;">
        <div style="background-color: #FF0000; color: white; padding: 10px 20px; border-radius: 5px; font-weight: bold;">
            Turtle
        </div>
    </a>
</div>

<br>

<!-- Contact Section -->
### Get in Touch

> Feel free to reach out if you'd like to collaborate or learn more about our work.

<p style="color: #a82ab1ff;">Open Coding Society: <a href="https://opencodingsociety.com" style="color: #f10a9cff; text-decoration: underline;">Socials</a></p>

<!-- Floating Balloons Code -->
<style>
  .balloon {
    position: fixed;
    width: 30px;
    height: 40px;
    background: pink;
    border-radius: 50% 50% 50% 50%;
    opacity: 0.8;
    animation: floatDown 10s linear infinite;
    z-index: 9999;
  }

  @keyframes floatDown {
    0% {
      transform: translateY(-100px) translateX(0);
      opacity: 1;
    }
    100% {
      transform: translateY(120vh) translateX(20px);
      opacity: 0;
    }
  }
</style>

<script>
  // Create multiple balloons
  function createBalloon() {
    const balloon = document.createElement('div');
    balloon.classList.add('balloon');

    // Random position and delay
    balloon.style.left = Math.random() * 100 + 'vw';
    balloon.style.animat


