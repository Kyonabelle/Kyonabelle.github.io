---
layout: landing
title: Photography
permalink: /photos/
image: assets/images/Photographybanner2.jpg
description: "professional events | personal events"
nav-menu: true
has_children: true

# photos:
#   set: berlin
#   size: 3
---

<!-- One -->
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

<!-- Division -->
<!-- <div class="row">
    <div class="6u 12u$(small)"> -->

<!-- Two -->
<section id="one">
  	<div class="inner">
		<header class="major">
			<h1>Instagram</h1>
        </header>

<!-- SnapWidget -->
<div class="snapwidget desktop">
<!-- SnapWidget -->
<!-- <script src="https://snapwidget.com/js/snapwidget.js"></script>
<iframe src="https://snapwidget.com/embed/864955" class="snapwidget-widget" allowtransparency="true" frameborder="0" scrolling="no" style="border:none; overflow:hidden;  width:100%; "></iframe> -->


<!-- SnapWidget -->
<script src="https://snapwidget.com/js/snapwidget.js"></script>
<iframe src="https://snapwidget.com/embed/864955" class="snapwidget-widget" allowtransparency="true" frameborder="0" scrolling="no" style="border:none; overflow:hidden;  width:80%; "></iframe>

