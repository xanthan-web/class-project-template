---
title: The Great Fermentation Debates of Our Time
layout: base
date: 2025-10-21
---

{% include images/jumbotron.html
  height="50vh"
  image-path="/assets/images/1920s-banner-3.png"
  title=""
%}

# 🥒 The Great Fermentation Debates of Our Time

{% include images/figure.html
  class="right"
  width="33%"
  caption="A very serious researcher contemplating kombucha"
  image-path="/assets/images/duke-ellington-nyc.jpg"
  source-url="https://commons.wikimedia.org/wiki/File:Xanthan.svg"
%}

Welcome to our groundbreaking research into one of humanity's greatest unsolved mysteries: **Is it fermentation or just spoilage in a jar?** 

On this site you will find webpages created by students in CLASS 101-B: Seriously Weird Topics Nobody Expected to Study. Each team of students was assigned a completely ridiculous research question about everyday objects, bizarre historical figures, or things nobody has ever asked about. They were asked to conduct REAL research, make evidence-based arguments, and present their findings with startling sincerity—despite the inherently absurd nature of their topic.

This semester's investigations include:
- Whether pigeons have secretly been running the government since 1987
- The untold story of why toast always lands butter-side down (PHYSICS OR CONSPIRACY?)
- A comprehensive timeline of the most dramatic socks in human history
- Whether hot dogs are sandwiches (spoiler: this one gets HEATED)

**👉 Ready to change this to YOUR project?** Just replace the title, topic, and swap in your own gorgeous research. Faculty: your students will see this silly example and think *"Hey, I can actually do something cool!"*
<br style="clear: both">

{% assign stories = site.pages | where_exp: "page", "page.path contains 'scrollstories/'" %}

{% include nav/card-grid.html cards = stories %}

<br style="clear: both">
