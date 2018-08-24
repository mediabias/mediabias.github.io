---
layout: default
permalink: /
title: "Latest Posts"
---

<!-- <div class="page-lead" style="background-image:url(https://mmistakes.github.io/skinny-bones-jekyll/images/wood-texture-1600x800.jpg)">
  <div class="wrap page-lead-content">
    <h1>Skinny Bones</h1>
    <h2>Jump start your Jekyll site with something thin and light.</h2>
    <a href="https://mmistakes.github.io/skinny-bones-jekyll/getting-started/" class="btn-inverse">Start Using Skinny Bones</a> &nbsp; or &nbsp; <a href="https://github.com/mmistakes/skinny-bones-jekyll" class="btn-inverse">View on GitHub</a>
  </div><!-- /.page-lead-content -->
<!-- </div>  -->


<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
