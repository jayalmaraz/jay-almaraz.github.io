---
layout: default
title: Home
nav_order: 1
description: "How to use Campfire, Campfire best practices & tutorials, volunteer management tips | Product guide."
permalink: /
---

# Onboarding and getting started

<style>
  body {
    width: 100%;
    height: 100%;
    margin: 0;
    padding: 0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
      "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji",
      "Segoe UI Emoji", "Segoe UI Symbol";
  }
  #cfg-main {
    margin: 0 auto;
    padding: 32px;
    display: grid;
    grid-gap: 32px;
  }
  .cfg-card:nth-child(1) {
    background-image: url(./assets/images/sail1.png);
    background-position: bottom;
  }
  .cfg-card:nth-child(2) {
    background-image: url(./assets/images/sail2.png);
    background-position: top;
  }
  .cfg-card:nth-child(3) {
    background-image: url(./assets/images/sail3.png);
    background-position: bottom;
  }
  .cfg-card:nth-child(4) {
    background-image: url(./assets/images/sail4.png);
    background-position: bottom;
  }
  .cfg-card {
    box-sizing: border-box;
    background-size: cover;
    background-position: bottom;
    display: flex;
    justify-self: start;
    width: 100%;
    height: 420px;
    border-radius: 8px;
    color: #e9e9e9 !important;
    text-decoration: none;
  }
  .cfg-card-content {
    padding: 32px;
    display: flex;
    flex-grow: 1;
    flex-direction: column;
    justify-content: center;
  }
  .cfg-card-content p,
  h2 {
    white-space: pre-line;
    color: #e9e9e9 !important;
  }
  @media (max-width: 798px) {
    #cfg-main {
      grid-template-columns: repeat(1, 360px);
      grid-gap: 8px;
    }
    .cfg-card {
      height: auto;
    }
    .cfg-card-content {
      padding: 0;
      padding-left: 16px;
      padding-right: 16px;
    }
    .cfg-card-content h2 {
      font-size: 1.25em;
      background-color: #242424 !important;
      padding: 16px;
      border-radius: 8px;
    }
    .cfg-card-content p {
      display: none;
    }
    .cfg-hover-text {
      display: none;
    }
  }
  @media (min-width: 799px) {
    #cfg-main {
      grid-template-columns: repeat(2, 360px);
    }
    .cfg-card-content h2 {
      margin-top: -32px;
      font-size: 1.75em;
    }
    .cfg-card-content p {
      padding-right: 64px;
    }
    .cfg-card:hover {
      cursor: pointer;
      color: #ffffff !important;
      border: none;
      text-decoration: none;
      box-shadow: 0 3px 7px -2px rgba(0, 0, 0, 0.2),
        0 3px 11px -1px rgba(0, 0, 0, 0.14),
        0 1px 24px -8px rgba(0, 0, 0, 0.12);
    }
  }
  .cfg-hover-text {
    height: 25px;
    opacity: 0;
    font-weight: bold;
    transition: opacity 0.3s ease-in;
  }
  .cfg-card:hover .cfg-hover-text {
    opacity: 1;
  }
</style>
<div id="cfg-main">
  <a href="/docs/sign-up" class="cfg-card">
    <div class="cfg-card-content">
      <h2>
        Signing up to Campfire
      </h2>
      <p>
        Join your team on Campfire! Learn how to create an account and set up your profile.
      </p>
      <span class="cfg-hover-text">
        Read the guide →
      </span>
    </div>
  </a>
  <a href="/docs/managers/uploading-content-with-resources" class="cfg-card">
    <div class="cfg-card-content">
      <h2>
        Upload content using Resources
      </h2>
      <p>
        Add your own files and information to Campfire as Resources.
      </p>
      <span class="cfg-hover-text">
        Read the guide →
      </span>
    </div>
  </a>
  <a href="/docs/managers/introduction-to-activities" class="cfg-card">
    <div class="cfg-card-content">
      <h2>
        Activities overview for managers
      </h2>
      <p>
        A quick rundown of the Activities Console layout and features for new managers.
      </p>
      <span class="cfg-hover-text">
        Read the guide →
      </span>
    </div>
  </a>
</div>
