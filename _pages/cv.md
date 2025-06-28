---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
  <ul>{% for post in site.educations reversed %}
    {% include archive-single.html %}
  {% endfor %}</ul>

Work experience
======
* 2022: AI Engineer
  * Magical API Company
  * I developed scalable AI web based services. The services  

* 2020-2022: Undergraduate Research Assistant
  * Ferdowsi, Mashhad, Iran, IP-PBX Lab
  * I researched and developed several anomaly detection methods in power consumption data. 
  * I worked with a team on designing and developing an anomaly detection platform as a service. 
  * Gained experience in machine learning, deep learning, data mining and big data handling with working under the supervision of Dr. Mohammadhossein Yaghmaei Moghadam.

* 2018: Nexus Team Member
  * Ferdowsi, Mashhad, Iran
  * Ferdowsi's robocup soccer simulation team member.
  * Participation in RoboCup Asia-Pacific 2018 as Nexus2D team member.
  
* 2019-2020: AI Developer
  * AITrends, Mashhad, Iran
  * I worked in Aitrends Company as an AI developer.
  * We had implemented several services with an excellent team, such as handwriting recognition service and House Pricing.

* 2018-2019: Android Developer
  * AITrends, Mashhad, Iran
  * I worked in Aitrends Company as an Android developer with an excellent team on several projects.

Extracurricular Activity
======

* 2022: Executive Committee Member
  * International Conference On Smart Cities, Internet of Things & Applications (<a href="https://sciot2022.um.ac.ir/Home/Committe?id=3">Link</a>)
  * Ferdowsi, Mashhad, Iran


Skills
======
  {% include skills-cv.html %}

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
