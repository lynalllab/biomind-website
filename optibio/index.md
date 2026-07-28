---
title: Optibio Research
nav:
  order: 4
  tooltip: Getting involved
---

<style>
  .optibio-wrapper {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 4rem;
    max-width: 1150px;
    margin: 5rem auto 5rem auto;
    padding: 0 2rem;
  }

  .optibio-text {
    flex: 1;
    max-width: 560px;
    text-align: left;
  }

  .optibio-text h1 {
    font-family: Georgia, serif;
    font-size: clamp(2.2rem, 4vw, 4.2rem);
    color: #4b2e83;
    font-weight: 700;
    line-height: 1.12;
    margin: 0 0 1.8rem 0;
  }

  .optibio-text p {
    font-size: 1.05rem;
    line-height: 1.65;
    color: #111111;
    margin: 0 0 1rem 0;
  }

  .optibio-image {
    flex: 1;
    max-width: 480px;
    text-align: center;
  }

  .optibio-image img {
    width: 100%;
    max-width: 480px;
    height: auto;
    display: block;
    margin: 0 auto;
  }

  @media (max-width: 800px) {
    .optibio-wrapper {
      flex-direction: column-reverse;
      gap: 2rem;
      margin: 2.5rem auto 3rem auto;
      padding: 0 1.5rem;
    }

    .optibio-text {
      text-align: center;
      max-width: 100%;
    }

    .optibio-text h1 {
      font-size: clamp(1.9rem, 9vw, 3rem);
      line-height: 1.15;
      margin-bottom: 1.5rem;
    }

    .optibio-text p {
      font-size: 1rem;
      line-height: 1.6;
    }

    .optibio-image {
      max-width: 360px;
      width: 100%;
    }

    .optibio-image img {
      max-width: 360px;
      width: 100%;
    }
  }
</style>

<div class="optibio-wrapper">

  <div class="optibio-text">

    <h1>Your cycle can tell an important story.</h1>

    <p>
      OptiBio is a new research study exploring how biological signals in the body change across time, lifestyle and the menstrual cycle. We are looking for people with different period experiences to help us understand what natural variation looks like in real life.
    </p>

    <p>
      Taking part means contributing to valuable health research, helping future scientific discovery, and receiving compensation for your time.
    </p>

    <p>
      OptiBio will be launching soon. Please check back shortly for more details.
    </p>

  </div>

  <div class="optibio-image">
    <img src="/optibio/optibio-bg-2.png">
  </div>

</div>

{% include search-info.html %}

{% include section.html %}

{% comment %}

Featured

...form coming soon...

{% endcomment %}
