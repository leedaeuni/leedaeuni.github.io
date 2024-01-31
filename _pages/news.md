---
layout: page
title: News
nav: true
nav_order: 4
permalink: /news/
---

<div class="news">
  {% if site.news != blank %}
    {% assign news_size = site.news | size %}
    <div
      class="table-responsive"
      {% if include.limit and site.announcements.scrollable and news_size > 3 %}
        style="max-height: 60vw"
      {% endif %}
    >
      <table class="table table-sm table-borderless">
        <!-- {% assign news = site.news | reverse %} -->
        {% if include.limit and site.announcements.limit %}
          {% assign news_limit = site.announcements.limit %}
        {% else %}
          {% assign news_limit = news_size %}
        {% endif %}

        {% include "_news/announcement_1 copy.md" %}


      </table>
    </div>
  {% else %}
    <p>No news so far...</p>
  {% endif %}
</div>





<!--  -->