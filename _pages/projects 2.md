---
layout: page
title: Projects
permalink: /projects/
description: A growing collection of your cool projects.
nav: true
---

<h3>Research Projects</h3>
<div class="projects grid">


  {% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "research" %}
        {% include single_project.html %}
    {% endif %}
    
  {% endfor %}

</div>



<h3>Class Projects</h3>

<div class="projects grid">
{% assign curr_projects = site.projects | sort: "importance" %}
  {% for project in curr_projects %}
    {% if project.type == "class" %}
        {% include single_project.html %}
    {% endif %}
    
  {% endfor %}

</div>


