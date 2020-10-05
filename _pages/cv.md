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
* B.Eng., Nanyang Technological University, 2014
* M.Eng., Nanyang Technological University, 2019

Work experience
======
* May 2013 - July 2013: Intern
  * Adventus Singapore Pte Ltd
  * Supervisor: [Mr. Tan Jaw Chyuan](https://www.linkedin.com/in/jaw-chyuan-tan-49484910)
  
* 2014 - 2019: Research Assistant
  * Nanyang Technological University
  * Supervisor: [Professor Li Mo](https://www.ntu.edu.sg/home/limo/)

* 2019 - now: Research Associate
  * Nanyang Technological University
  * Supervisor: [Professor Li Mo](https://www.ntu.edu.sg/home/limo/)
  
Skills
======
* Data Processing & Analytics
  * MATLAB
  * NumPy, SciPy, Pandas, Matplotlib
* Web Design & Dashboard
  * HTML, CSS, JavaScript, JQuery
  * PHP
* Database Design & Management
  * MySQL
  * MSSQL
  * PostgreSQL
* Embedded System Development
  * TinyOS
  * ContikiOS
  * Arduino
* General Programming
  * Python
  * C programming
  * C++
  * C#
  * Java
  
Demos
======
* [IoT Dashboard](https://wands.sg/research/iot/dashboard/)
  * Designed dashboard based on PHP, Javascript, HTML, CSS
  * Setup and deploy database using Amazon RDS
  * Setup dashboard on EC2 instance
  * Developed LoRa sensor hardware for demo
  * Developed LoRa gateway to receive sensor data
  * Developed Cloud agent to parse received data from gateway

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
