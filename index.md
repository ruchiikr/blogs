---
layout: default
title: "Blog"
---

# Latest Blog Posts

{% for post in site.posts %}

  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>  
{% endfor %}

<p>This post is about how to hire a Full-Stack Developer, covering essential skills, qualifications, and the hiring process.</p>
