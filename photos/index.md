---
layout: landing
title: Photography
permalink: /photos/
image: assets/images/Photographybanner2.jpg
description: "professional events | personal events"
nav-menu: true
has_children: true

photos:
  set: berlin
  size: 3
---

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>Instagram</h1>
        </header>
<!-- SnapWidget -->
<iframe src="https://snapwidget.com/embed/633817" class="snapwidget-widget" allowtransparency="true" frameborder="0" scrolling="no" style="border:none; overflow:hidden;  width:495px; height:495px"></iframe>

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h1>Projects</h1> 
    	</header>

<ul id="specialUl" >
  {% comment %}
    Get all "photo_set" pages and display a list with links to them.
  {% endcomment %}
  {% assign photo_pages = site.pages | where: "layout", "photo_set" %}
  {% for photo_page in photo_pages %}
    <li>
      <h3><a href="{{ photo_page.url | prepend: site.baseurl }}">{{ photo_page.title }}</a></h3>
    </li>
  {% endfor %}
</ul>
