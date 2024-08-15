---
layout: page
permalink: /generate/
title: Create Your Bachelor Party Song
description: Engage with your crew to create the perfect funny song for the bachelor party!
---

<section class="engagement">
  <div class="container">
    <h1>Let's Create the Perfect Song for {{ page.title }}</h1>
    <p>Gather your crew and share your best memories to craft a hilarious and personalized song for the groom!</p>
  </div>
</section>

<section class="form-section">
  <div class="container">
    <h2>Fill Out the Form Below</h2>
    <form action="/submit-song" method="post">
      <div class="form-group">
        <label for="bachelor-name">Name of the Bachelor:</label>
        <input type="text" id="bachelor-name" name="bachelor_name" required>
      </div>
      <div class="form-group">
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="funny-episodes">Funny Episodes You Experienced Together:</label>
        <textarea id="funny-episodes" name="funny_episodes" rows="4" required></textarea>
      </div>
      <div class="form-group">
        <label for="landmarks">Geographical Landmarks You Have Lived, Partied, Had Good Times In:</label>
        <textarea id="landmarks" name="landmarks" rows="4" required></textarea>
      </div>
      <div class="form-group">
        <label for="crew-descriptors">Words That Describe You and Your Crew Well:</label>
        <input type="text" id="crew-descriptors" name="crew_descriptors" required>
      </div>
      <button type="submit" class="btn btn-primary">Create My Song!</button>
    </form>
  </div>
</section>

<section class="engagement-footer">
  <div class="container">
    <p>Once you submit the form, our AI will generate a personalized song that captures the essence of your crew and the fun times you've shared. Get ready to make the groom laugh!</p>
  </div>
</section>
