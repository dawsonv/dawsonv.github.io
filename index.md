---
layout: default
title: Home
---

<style>
  .intro-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 20px;
    margin-top: 20px;
  }

  .profile-pic {
    width: 100%;
    max-width: 200px; /* Reduced to be much smaller */
    height: auto;
    border-radius: 8px;
  }

  .intro-text {
    width: 100%;
    text-align: left;
  }

  @media (min-width: 768px) {
    .intro-container {
      display: grid;
      grid-template-columns: 1fr 1fr; /* 50/50 split on desktop */
      align-items: center;
      gap: 40px;
      margin-top: 60px;
      text-align: left;
    }

    .profile-pic {
      justify-self: center; /* Centers the smaller image within its 50% half */
    }

    .intro-text {
      width: auto;
    }
  }
</style>

<div class="intro-container">
  <div class="intro-text">
    <div style="font-size: 2.5em; font-weight: bold; margin-bottom: 32px;">Hey, I'm Dawson!</div>

    I'm a student and researcher at UC Berkeley focused on energy systems, data science, and policy. I'm passionate about using computational tools to accelerate decarbonization and the global energy transition.
    {:.lead}
  </div>

  <img src="/assets/dawson.jpg" alt="A picture of me in Oakland, where I live" class="profile-pic"/>
</div>
