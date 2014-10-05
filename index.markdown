---
layout: default
---

A collection of beautiful, hand-crafted Notations for Krithis, Keerthanas, Varnams and other carnatic compositions. I create these scores for my own personal use. Licensed under Creative Commons. Free to download, print, and share for non-commercial purposes.

![Carnatic Score Sample][sample]


<div class="home">

  <h1 class="page-heading">Scores</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>


[sample]: images/carnatic_scores-sample.png "Excerpt from Ennaganu Rama Bhajana by Bhadrachala Ramadas"
