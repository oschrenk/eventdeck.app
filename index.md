---
layout: blocks
title: Homepage
date: 2020-02-23T23:00:00.000+00:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/assets/logo.svg"
  navigation:
  - link: "/"
    link_text: Home
  - link: "#features"
    link_text: Features
  - link: "#privacy"
    link_text: Privacy
  cta:
    url: mailto:eventdeck@oschrenk.com
    button_text: Contact
- template: hero-banner-w-image
  block: hero-2
  headline: Gloomhaven <br><strong>eventdeck</strong>
  content: Never forget the effects of an event again.
  cta:
    enabled: false
    url: https://github.com/forestryio/ubuild-jekyll
    button_text: 'See on GitHub '
  image:
    image: "/assets/hero-home.png"
    alt_text: Home Screen
  background_image: "/assets/hero-2-bg.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: <strong>History<span class="light">&nbsp;</span></strong><span
    class="light">helps you to remember past events</span>
  content: All past events in one place.
  media:
    image: "/assets/hero-history.png"
    alt_text: Menu
- template: content-feature
  block: feature-1
  media_alignment: Right
  headline: <strong>Choose available events</strong><span class="light">&nbsp;when you unlock new classes or cards</span>
  content:
  media:
    image: "/assets/hero-city.png"
    alt_text: Unlock events
- template: content-feature
  block: one-column-1
  headline: Privacy Policy

---
