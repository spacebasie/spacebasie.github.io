---
permalink: /
title: "Hello World!"
excerpt: "Hello World!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome to my world wide web page of wizardly crafts.

I recently wrapped up my work with [LaelapsAI](/experience/) where I took ownership of the computer vision stack. 

I hold an MSc in Communications & Signal Processing from Imperial. My [research thesis](/research/) focused on **representation learning and distributed optimization for multi-agent systems** in the CSP lab.

## Mission
My passion lies at the intersection of **computational science, Earth observation, and efficient digital agriculture**. I wish to hone my engineering skill-set to contribute in bridging the gap between software and hardware systems for enhancing environmentally conscious decision-making.

Whether I am working to:
* Optimize satellite data to monitor emissions or forestation projects
* Build software for cheap sensors to analyze soil health in an agricultural field
* Develop safer autonomous vehicle sensor systems to reduce accidents on the road

I am driven by ensuring that new-age tech can assist us towards a greener earth.

## Future Endeavors
I am currently seeking full-time opportunities in **machine learning, computer vision and data engineering roles** with potential applications in:
* Environmental monitoring
* Geospatial analysis
* Digital agriculture
* Autonomous robotics (cars/transportation)


## Selected Projects
<div class="project-grid">
{%- for project in site.data.projects -%}
  <div class="project-card">
    <p class="project-meta">{{ project.meta }}</p>
    <p class="project-title">{{ project.title }}</p>
    <p class="project-desc">{{ project.desc }}</p>
    {%- if project.links -%}
    <p class="project-links">{%- for link in project.links -%}<a href="{{ link.url }}">{{ link.label }}</a>{%- endfor -%}</p>
    {%- endif -%}
  </div>
{%- endfor -%}
</div>

More on the [projects page](/portfolio/).

## News
<ul class="news-list">
{%- for item in site.data.news -%}
  <li><span class="news-date">{{ item.date }}</span><span class="news-text">{{ item.text | markdownify | remove: "<p>" | remove: "</p>" | strip }}</span></li>
{%- endfor -%}
</ul>

War is over, if you want it.