---
layout: page
title: About
permalink: /about/
---

<style>
  .about-wrapper {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
    align-items: center;
    margin: 0 auto;
    max-width: 900px;
    padding: 0 1rem;
  }

  .about-photo {
    order: 2;
    width: 220px;
  }

  .about-photo img {
    width: 100%;
    display: block;
    border-radius: 12px 0 ;
  }

  .about-content {
    order: 1;
  }

  @media (min-width: 768px) {
    .about-wrapper {
      flex-direction: row;
      align-items: flex-start;
      justify-content: center;
    }

    .about-photo {
      order: 1;
      margin-right: 2rem;
    }

    .about-content {
      order: 2;
    }
  }
</style>

<div class="about-wrapper">
  <div class="about-photo">
    <img src="/assets/lana.jpg" alt="Lana" />
  </div>

  <div class="about-content">
    Hi,
    <p>My name is Lana and I am a software developer 😀. Web developer during a day, everything-else developer at night.</p>

    <p>
      Ruby, JavaScript, HTML, CSS are my very good friends. Recently Rust joined the close frienship circle 🦀
      <br /> And I am always open to learn something new.
    </p>

    <p>
      Currently I am working at
      <a href="https://www.shopify.ca/">Shopify</a> and we are constantly hiring. If you
      are awesome please join us, here some
      <a href="https://www.shopify.ca/careers/search">openings</a>
    </p>

    <p>
      <strike>I am also working on my own project. This is a new exciting educational
      platform. OwlDot Educards is a classic flashcards application. Please,
      visit at
      <a href="https://www.owldot.com">www.owldot.com</a>
      </strike>
      <br/>
      <b>OwlDot is currently paused. New ideas are brewing. Thanks everyone for being a part of the journey!</b>
    </p>

    <p>
      I will be glad to hear from you at
      <a href="https://www.linkedin.com/in/lanadz/">LinkedIn</a> or by
      <a href="mailto:svitlana.dzyuban@gmail.com">email</a>
    </p>

    <p>Cheers,</p>
    <p>Lana</p>
  </div>
</div>
