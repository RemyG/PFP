---
layout: page
title: PFP
---

<div class="grid-container">
	<div class="grid-100 main-description">
		<p>PFP is a tiny PHP application framework built for people who use a LAMP stack. PFP aims to be as simple as possible to set up and use.</p>
		<p>This version is a fork of the original PIP project by <a href="http://gilbert.pellegrom.me/">Gilbert Pellegrom</a>. You can find the original project at <a href="https://github.com/gilbitron/PIP/">https://github.com/gilbitron/PIP/</a>.</p>
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
