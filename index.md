---
layout: page
title: Art-Tech
tagline: Do you know you can have Master in Arts even though you are a computer science major?
---
{% include JB/setup %}


## Responsive web data analytics

Design goals:
- As simple as using excel
- Being able to answer an analytical question with a few intuitive touches
- WYSIWYI (What You See Is What You Interact)

Technologies:
- HTML5, CSS3, Javascript, Jquery, Crossfilter, D3.js, DC.js, NV.js
- Ruby on Rails
- Postgresql

Demo to come soon.

## Twitter analytics

Example graph of information flow on Twitter sphere:
<img class="brand-image" src="{{ASSET_PATH}}/images/twitter_activity_graph.png"/>

Goals:
- Real time aggregate and analyze tweets on a certain topic
- Trend discovery
- Graph of user activities on the topic

Technologies:
- Javascript, Canvas, Sigma.js
- Twitter streaming API, Ruby

## Social Islands
A graph visualization of Facebook friends network.



This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


