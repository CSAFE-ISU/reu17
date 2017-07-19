---
layout: default
title: "CSAFE @ ISU REU"
css: "/css/index.css"
---

<div class="list-filters">
  <a href="/reu17" class="list-filter">All posts</a>
  <a href="/reu17/assignments" class="list-filter filter-selected">Assignments</a>
    <a href="/reu17/week1" class="list-filter">June 12-16, 2017</a>
  <a href="/reu17/week2" class="list-filter">June 19-23, 2017</a>
  <a href="/reu17/week3" class="list-filter">June 26-30, 2017</a>
  <a href="/reu17/week4" class="list-filter">July 3-7, 2017</a>
  <a href="/reu17/week5" class="list-filter">July 10-14, 2017</a>
  <a href="/reu17/week6" class="list-filter">July 17-21, 2017</a>
  <a href="/reu17/week7" class="list-filter">July 24-28, 2017</a>
</div>

<div class="posts-list">
  {% for post in site.tags.week1 %}
  <article>
    <a class="post-preview" href="{{ post.url | prepend: site.baseurl }}">
	    <h2 class="post-title">{{ post.title }}</h2>
	
	    {% if post.subtitle %}
	    <h3 class="post-subtitle">
	      {{ post.subtitle }}
	    </h3>
	    {% endif %}
      <p class="post-meta">
        Posted on {{ post.date | date: "%B %-d, %Y" }}
      </p>

      <div class="post-entry">
        {{ post.content | truncatewords: 50 | strip_html | xml_escape}}
        <span href="{{ post.url | prepend: site.baseurl }}" class="post-read-more">[Read&nbsp;More]</span>
      </div>
    </a>  
   </article>
  {% endfor %}
</div>