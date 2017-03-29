---
layout: page
title: VBS
permalink: /vbs/
---

<div class="row">

<div class="four columns" id="vbs-sidebar" markdown="block">

## Register soon! ##

## Details ##

{% for detail in site.data.vbsdetails %}
<div class="vbs-sidebar-row">
	<div class="vbs-sidebar-label">{{ detail.label }}</div>
	<div class="vbs-sidebar-content">{{ detail.content }}</div>
</div>
{% endfor %}
</div>

<div class="eight columns" markdown="block">

## From previous years ##

![](/img/vbs2015-1.jpg){:class="image-full"}

![](/img/vbs2015-2.jpg){:class="image-full"}

</div>
</div>
