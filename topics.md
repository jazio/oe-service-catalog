---
layout: page
permalink: /topics/
title: Categories
---

<div class="message">
  Sorry, your browser does not support CSS Grid.
</div>
<section class="section">
  <div class="grid">

    {% for post in site.posts %}
    <div class="item">
      <div class="item__details">
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </div>
    </div>
    {% endfor %}

</div>
</section>
