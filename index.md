---
layout: default
title: Sebastian Mostek
---

## Welcome


![Profile Picture]({{ "assets/images/Professional_PFP.jpg" | relative_url }}){: class="profile-image"}

 
My name is {{ site.name }}, and I have just finished my seventh semester at Cornell University, graduating with a degree in Mechanical Engineering. Ever a generalist, while some fields like renewable energy and additive manufacturing have recieved a bit more of my attention, if I can be said to have a true expertise it is in pure math and physics, which has proven invaluable to my ability to quickly expand my practical knowledge to new fields.

This site serves to catalogue and present the many projects I've worked on and skills I've learned, as well as being a digital home for <a href="{{ "/cv/" | relative_url }}">my resume</a>. For a pdf of mostly the same portfolio content as this site, click [here]({{ "assets/Technical_Portfolio.pdf" | relative_url }}).


### Projects & Coursework
<div class="gallery-container">
<div class="project-gallery">
    {% for project in site.projects %}
      <div class="gallery-item">
        <a href="{{ project.url | relative_url }}">
          <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
          <p>{{ project.title}}</p>
        </a>
      </div>
    {% endfor %}
</div>
</div>
