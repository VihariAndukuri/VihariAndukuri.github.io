---
layout: page
title: Books
permalink: /books/
---

Some Books I enjoy

<div class="archive">
  {% for post in site.posts %} {% assign currDate = post.date | date: "%Y" %} {%
  if currDate != date %}
  <h1 class="archive-year">{{ currDate }}</h1>
  {% assign date = currDate %} {% endif %}
  <div class="archive-item">
    <span class="post-date archive-date fs-4"
      >{{ post.date | date: "%B %d, %Y" }}</span
    >
    <a href="{{ post.url | relative_url }}" class="archive-title fs-4"
      >{{ post.title }}</a
    >
  </div>
  {% endfor %}
</div>

![Chungking Express Screencap 1]({{site.baseurl}}/assets/images/sample_portfolio/1.jpg)
![Chungking Express Screencap 2]({{site.baseurl}}/assets/images/sample_portfolio/2.jpg)
![Chungking Express Screencap 3]({{site.baseurl}}/assets/images/sample_portfolio/3.jpg)
![Chungking Express Screencap 4]({{site.baseurl}}/assets/images/sample_portfolio/4.jpg)
![Chungking Express Screencap 5]({{site.baseurl}}/assets/images/sample_portfolio/5.jpg)
