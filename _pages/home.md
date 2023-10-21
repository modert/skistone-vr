---
layout: splash
title: ""
permalink: /
hidden: true
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/header.jpg
  show_overlay_exerpt: true
  overlay_centered: true
  actions:
    - label: "Book Direct"
      url: "/booking"
excerpt: "Your mountain getaway for relaxation, skiing, hiking, biking and a whole lot more!"
intro: 
  - excerpt: "Wake up with the sun rising from behind the fantastic mountain views in this east facing third floor Silver Mill condo, then enjoy your morning coffee on the covered balcony with the warm sun against the cool air. If it's too cold for you on the balcony, come back inside and enjoy that coffee by the gas fireplace."
feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    type: "center"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: /assets/images/4.jpg
    alt: "Bathroom"
    title: "Bathroom"
    excerpt: "We gave the bathroom a little update in June of 2023"
feature_row3:
  - image_path: /assets/images/6.jpg
    alt: "Rec Room"
    title: "Recreation Room"
    excerpt: 'Watch the game on the brand new 70" TV while you shoot some pool!'
feature_row4:
  - image_path: "/assets/images/Skistone Vacation Rentals.png"
    alt: "Skistone Vacation Rentals Logo"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}