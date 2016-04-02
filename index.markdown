---
layout: default
title: Ilham's corner
---



<div class="posts">
    {% for post in site.posts %}
    <a class="item" href="{{ post.url }}">
    	<div class="right">
    		<p>{{ post.title }}</p>
    		<span>{{ post.date | date_to_string }}</span>
    	</div>
    	<div class="left">
    		
    	</div>
    </a>
    {% endfor %}
</div>

<br />
<hr />
<blockquote>
Wechat:2286611044&nbsp;|&nbsp;<a href="http://github.com/ilhamxyz/">Github</a>
</blockquote>
