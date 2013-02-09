---
layout: page
title: Gorilla-Studios
tagline: Photography &amp; Design
---
<div class="m_blog">
{% for post in site.posts limit:10 %}
<div class="m_post_date"><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a> &raquo; <span>{{ post.date | date_to_string }}</span></div>
<div class="post">
  {% include JB/post_content %}
  <hr>
</div>
  {% endfor %}
<div class="post">
  <p><a href="/archive.html">Older Posts &raquo;</a></p>
</div>
</div>

<div class="m_sidebar cf">
    <div class="affiliate_link">
      <p><a href="http://www.borrowlenses.com?blpid=gorilla-studios&amp;a_bid=265e95f3" target="_top"> </a></p>
    </div>

  <div class="twitter_container">
    <h5>Tweets</h5>
    <div class="tweet"></div>
  </div>
</div>

