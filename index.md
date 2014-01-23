---
layout: page
title: I LOVE YOU,THE WORLD!
tagline: Supporting tagline
---
{% include JB/setup %}
<h2>{{page.title}}</h2>
<p>кЫспндуб</p>
{% for post in site.posts %}
   <li>{{ post.date | date_to_string}}<a href="{{site.baseurl}}{{post.url}}">{{post.title}}</a></li>
{%endfor%}




