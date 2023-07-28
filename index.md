---
layout: default
---
# Justin's Two Bytes &#128126;
*To help me postpone LLM dependence*

<div class="posts-list">
    {% for post in site.posts %}
    <div class="post">
        <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        <p>{{ post.date | date: "%B %d, %Y" }}</p>
    </div>
    {% endfor %}
</div>