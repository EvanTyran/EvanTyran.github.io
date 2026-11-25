---
layout: default
title: Evan Tyran
---

## About

I'm a data scientist and analyst with 10+ years of experience in supply chain analytics and category management across consumer products, including household cleaning, sleep products, tires and auto parts, and home renovation.

I'm an IBF-certified forecaster, and statistical forecasting is the work I enjoy most. In my last role I replaced a manual, salesperson-driven forecast with a statistical model built on moving averages and LightGBM. I'm a statistician at heart, and I like finding new applications for different models.

## What I work with

Python, Power BI, SQL, and syndicated point-of-sale data.

## What I'm building

Notebook-based projects in forecasting, causal inference, and classification, including a Rotten Tomatoes critic-versus-audience regression and a Best Picture Oscar difference-in-differences analysis. I also write a Substack about pop culture through a data science lens: finding the signal in the noise.

## My Projects

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%-d %b %Y" }}
{% endfor %}

## Find me

- [Substack](https://evantyran.substack.com/)
- [LinkedIn](https://www.linkedin.com/in/evan-tyran-cpf-26027586/)
