---
title: "Zhang Lab - Miscellanies"
layout: textlay
excerpt: "Miscellanies"
sitemap: false
permalink: /misc
---

### Interesting papers

<div class="row">
<div class="col-sm-12 clearfix">
 <div class="well">
  <!-- <h4> Interesting papers </h4> -->
  <ul style="overflow: hidden">
  {% for misc in site.data.miscpaperlist %}
  {% if misc.highlight == 1 %}
  <li> 
   {{ misc.title }}, <strong><a href="{{ misc.link.url }}">{{ misc.link.display }}</a></strong>
  </li>
  {% endif %}
  {% endfor %}
  </ul>
 </div>
</div>
</div>

<p> &nbsp; </p>

<p> &nbsp; </p>
