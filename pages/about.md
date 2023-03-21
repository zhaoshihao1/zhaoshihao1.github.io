---
layout: page
title: About
description: Talk is cheap, show me your code
keywords: Shihao Zhao, 赵士豪
comments: true
menu: 关于
permalink: /about/
---


I'm Shihao Zhao, a software developer.

Currently living in Markham, Ontario, Canada.


## Contact(联系)

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
</ul>


## Skill Sets(技术栈)

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}
