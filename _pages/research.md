---
title: "Zhang Lab - Research"
layout: gridlay
excerpt: "Zhang Lab -- Research"
sitemap: false
permalink: /research/
---

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

## Current research

{% for res in site.data.researchlist %}

{% if res.highlight == 1 %}

<div class="row">

<div class="col-sm-12 clearfix">
 <div class="well">
  <h4><b>{{ res.title }}</b></h4>
  <h5> {{ res.short }}</h5>
  <img src="{{ site.url }}{{ site.baseurl }}/images/slider/{{ res.image }}" class="img-responsive" width="45%" style="float: left" />
  <p>{{ res.description }}</p>
  <p>{{ res.description2 }}</p>
 </div>
</div>

</div>

{% endif %}
{% endfor %}

<p> &nbsp; </p>


## Previous research

{% for res in site.data.previousresearchlist %}

{% if res.highlight == 1 %}

<div class="row">

<div class="col-sm-12 clearfix">
 <div class="well">
  <h4><b>{{ res.title }}</b></h4>
  <!--  <h5> {{ res.short }}</h5> -->
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ res.image }}" class="img-responsive" width="35%" style="float: left" />
  <p>{{ res.description }}</p>
  <p>{{ res.description2 }}</p>
  <p><strong>{{ res.references }}</strong></p>
 </div>
</div>

</div>

{% endif %}
{% endfor %}

<p> &nbsp; </p>


