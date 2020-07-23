---
permalink: /
title: "Gen"
layout: splash

header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: assets/images/patrick-boucher-70pm04yEWTA-unsplash.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
excerpt: "Gen.jl is a general-purpose probabilistic programming system, embedded in Julia."

intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

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
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

feature_row2:
  - image_path: /assets/images/hybrid.png
    alt: "placeholder image 2"
    title: "Gen supports custom hybrid inference algorithms"
    excerpt: 'Neural network inference is fast, but can be inaccurate on out-of-distribution data, and requires expensive training. Model-based inference is more computationally expensive, but does not require retraining, and can be more accurate. Gen supports custom hybrid inference algorithms that benefit from the strengths of both approaches.'

feature_row3:
  - image_path: /assets/images/trace.png
    alt: "placeholder image 2"
    title: "Gen users implement custom algorithms without extending the language implementation"
    excerpt: 'Instead of an inference engine, Gen provides a flexible "Trace" data type for implementing an open-ended set of inference and learning algorithms without touching the modeling-language implementation. Gen trace operations includes automatic differentiation (AD), but goes beyond AD and includes other operations needed for model-based reasoning.'

feature_row4:
  - image_path: /assets/images/open-universe.png
    alt: "placeholder image 2"
    title: "Gen supports inference in open-universe models"
    excerpt: 'Generative and inference models in Gen can have stochastic control flow (dimension). Support for custom reversible jump MCMC allows for much more efficient inference over model structure.'

feature_row5:
  - image_path: /assets/images/extensible.png
    alt: "placeholder image 2"
    title: "Gen is extensible"
    excerpt: 'Gen is designed for extensibility and to support incremental performance optimization as the inference application is scaled from a small-scale proof of concept to a prototype. Users can optimize bottlenecks in their model by hand-optimized code that inter-operates with Gens inference library code.'

---

# What is probabilistic programming?
{: style="text-align: center"}

Probabilistic programming is the intersection of software engineering and probabilistic modeling, inference, and learning. Probabilistic programming systems are tools that make it easier to implement probabilistic inference and learning algorithms; analogously to how deep learning frameworks make it easier to implement and train and deploy neural networks. Probabilistic programing systems have a long history. 

# Why Gen?
{: style="text-align: center"}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="right" %}

# What has Gen been used for?
{: style="text-align: center"}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row5" type="right" %}
