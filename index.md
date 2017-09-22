---
layout: page
title: PFP
---

# {{ page.title }}

<div class="grid-container">
	<div class="grid-100 main-description">
		
	</div>
</div>

<div class="grid-container">
	<div class="grid-50 tablet-grid-50">
		<h3>Latest posts</h3>
		<ul class="home-list">
			{% for post in site.posts limit: 5 %}
				<li>
					<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
					<small><i class="icon-time"> </i>{{ post.date | date:"%Y-%m-%d" }}</small>
				</li>
			{% endfor %}
		</ul>
	</div>
	<div class="grid-50 tablet-grid-50">
		<h3>Links</h3>
		<ul class="home-list">
			<li><a href="https://github.com/RemyG/PFP">PFP on Github</a></li>
		</ul>
	</div>
</div>
