---
layout: home
permalink: "/"
title: "Honesty Wild"
description: "Advance is a multi-purpose premium Jekyll theme. Modern design, clean code and highly configurable."
header_transparent: true
meta_title: Honesty Wild - Interactive Content Developer

hero:
  enabled: true
  heading: "IMMERSIVE EXPERIENCE<br>DESIGN STUDIO"
  sub_heading: "We create games and special purpose XR contents" # <br>다목적 실감 콘텐츠 및 게임 개발 전문 기업"
  text_color: "#FFFFFF"
  background_color: "#295A52" #1d2830
  background_gradient: true
  background_image: "/assets/images/gen/home/home-1-large.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: false
  height: "660px"
  buttons:
    enabled: false
    list:
      - text: "Buy Now"
        url: "https://www.zerostatic.io/theme/jekyll-advance/"
        external: true
        fa_icon: false
        size: large # "small", "normal", "large"
        outline: false
        style: "light" # "light", "dark", "primary"
      - text: "Documentation"
        url: "https://www.zerostatic.io/docs/jekyll-advance/v2.0/"
        external: true
        fa_icon: false
        size: large
        outline: true
        style: "light"

services:
  enabled: true
  heading: "BUSINESS"
  sub_heading: ""
  limit: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Business"
  view_more_button_link: "/services"

intro:
  enabled: false
  align: left
  image: "/assets/images/gen/content/content-6-thumbnail.webp"
  heading: "We've helped hundreds of people grow their business online."
  sub_heading: ""
  features:
    enabled: true
    list:
      - text: "Configure the homepage sections in front-matter."
        fa_icon: "fas fa-check"
      - text: "An advanced hero image section with dozens of design options."
        fa_icon: "fas fa-check"
      - text: "Fully responsive and SEO optimised."
        fa_icon: "fas fa-check"
      - text: "Multiple content types including services, projects, blog and more."
        fa_icon: "fas fa-check"
  buttons:
    enabled: true
    list:
      - text: "About Us"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: false
  limit: 5
  sort: "weight" # 'date'

projects:
  enabled: true
  heading: "Our Projects"
  sub_heading: ""
  limit: 2
  columns: 2
  sort: "weight" # 'date'
  view_more_button_text: "View All Projects"
  view_more_button_link: "/projects"

outro:
  enabled: true
  align: center
  image: false
  heading: Get Started Today
  sub_heading:
  features:
    enabled: false
    list:
      - text: "Free Quote"
        fa_icon: "fas fa-envelope-open-text"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "mailto:joon@honestywild.com"
        external: false
        size: "large"

posts:
  enabled: true
  heading: "Latest Posts"
  sub_heading: ""
  limit: 3
  columns: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Posts"
  view_more_button_link: "/blog"
---
