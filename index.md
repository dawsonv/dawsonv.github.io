---
layout: default
title: Home
---

<style>
  :root {
    --intro-vertical-align: center; /* Options: start, center, end */
  }

  .intro-container {
    display: flex;
    flex-direction: column;
    align-items: var(--intro-vertical-align);
    text-align: center;
    gap: 20px;
    margin-top: 20px;
  }

  .profile-pic {
    width: 100%;
    max-width: 160px; /* Reduced for more breathing room */
    height: auto;
    border-radius: 8px;
  }

  .pic-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
  }

  .pic-caption {
    font-size: 0.75em;
    color: #6a737d;
    line-height: 1.2;
    white-space: nowrap; /* Keep on one line */
  }

  .intro-text {
    width: 100%;
    text-align: left;
  }

  @media (min-width: 768px) {
    .intro-container {
      display: grid;
      grid-template-columns: 1.2fr 1fr; /* Text gets slightly more room */
      align-items: var(--intro-vertical-align);
      gap: 80px; 
      margin-top: 20px;
      text-align: left;
    }

    .pic-container {
      justify-self: center; /* Centers the image/caption within its half */
    }

    .intro-text {
      width: auto;
    }
  }
</style>

<div class="intro-container">
  <div class="intro-text">
    <div style="font-size: 1.2em; margin-bottom: 16px;">
      <strong>Hey, I'm Dawson!</strong> I'm a software developer focused on energy systems, data science, and policy. I use machine learning to accelerate decarbonization and the global energy transition.
    </div>
  </div>

  <div class="pic-container">
    <img src="/assets/dawson.jpg" alt="A picture of me in Oakland, where I live" class="profile-pic"/>
    <div class="pic-caption"></div>
  </div>
</div>
