---
layout: default
title:  UNI Math 4159/5159 <br class="visible-xs" /><i>Knot Theory</i>
---

<div class="row">
  <div class="col-xs-12">
    <p class="lead">
      This is the course web site for <i>Knot Theory</i>.
      Here you can find all of the documentation for class, including a
      syllabus, a list of resources, and the class blog.
    </p>
  </div>
</div>

<div class="row">
  <div class="col-xs-12">
    {% for post in site.posts %}
	  <div class="post">
		  <h3 class="title">
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}
        </a>
      </h3>
		  <p class="meta">
        Date: {{ post.date }}
      </p>
		  <div class="entry">
		    {{ post.content | truncatewords: 50}}
		  </div>
	  </div>
    {% endfor %}
  </div>
</div>

<div class="row visible-xs visible-sm">
 <p><br /></p>
</div>
