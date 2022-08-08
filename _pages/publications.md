---
layout: archive
title: "Resume"
permalink: /resume/
author_profile: true
---

[Download resume here](http://daryapetrov.github.io/files/resume.pdf)

<embed src="http://daryapetrov.github.io/files/resume.pdf" width="500" height="375" 
 type="application/pdf">

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
