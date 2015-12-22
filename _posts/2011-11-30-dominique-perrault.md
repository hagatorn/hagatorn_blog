---
layout: post
title: In Interview With Dominique Perrault
date: '2011-11-30 10:49:08 +0000'
categories: Writing
tags:
- Architecture
- Interview

---

{% assign interview-data = site.data.interviews.perrault %}
{% assign interview=interview-data.interview %}

{% for qna in interview %}
  {% assign q=qna.question  %}
  {% assign a=qna.answer  %} 
  {% include interview-part.html data = q type = "question"%}
  {% include interview-part.html data = a type = "answer" %}
{% endfor %}

{% assign publication-data=interview-data.publication %}
{% assign publication = publication-data.publication  %}
{% assign publisher = publication-data.publisher  %}


{{ interview-data.interviewee.name }} spoke to Eva Guttmann and Craig Chamberlain on behalf of the {{interview-data.client.name}}, Graz, {{ interview-data.date | date: "%B %d, %y" }}.
This interview was first published by the {{ publisher.name }} in the {{interview-data.client.name}}'s, "{{ publication.name }}" annual.


{% include amazon-link.html asin=publication.amazon.asin locale=publication.amazon.locale %}
