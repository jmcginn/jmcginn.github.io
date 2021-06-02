---
title: "splashpage"
layout: splash
feature_row:
  - image_path: /assets/images/guitar.jpeg
    url: /music/ 
    title: "Music"
    excerpt: "Some of my guitar playing"
  - image_path: /assets/images/dread.jpg
    title: "Miniature painting"
    excerpt: "Enjoyable colouring in"
    #url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--inverse"
  - image_path: /assets/images/neuron.png
    title: "Research"
    excerpt: "Astrophysics and python tutorials"
feature_row3:
  - image_path: /assets/images/guitarsplash.jpeg
    alt: "placeholder image 2"
    title: "Hi, welcome to Jordan's webpage"
    excerpt: 'This will eventually be something that I want to use as a place to host my interests. Astrophysics/machine learning, guitar playing, miniature painting, magic and anything else I stumble into.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---
{% include feature_row id="feature_row3" type="right" %}
{% include feature_row %}
