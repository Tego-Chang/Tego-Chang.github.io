---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- [Some title here](FILE_NAME.pdf) -->
<!-- ![Resume](/files/CV_TegoChang.pdf) -->
Test of CV
  <!-- <html>
    <head>
      <object data="https://Tego-Chang.github.io/files/CV_TegoChang.pdf" type="CV">
        <embed src="https://Tego-Chang.github.io/files/CV_TegoChang.pdf">
          <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://Tego-Chang.github.io/files/CV_TegoChang.pdf">Download PDF</a>.
          </p>
        </embed>
      </object>
    </head>
  </html> -->
  <html>
    <object data="https://Tego-Chang.github.io/files/CV_TegoChang.pdf" type="pdf">
        <embed src="https://Tego-Chang.github.io/files/CV_TegoChang.pdf" type="pdf">
            <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://Tego-Chang.github.io/files/CV_TegoChang.pdf">Download PDF</a>.</p>
        </embed>
    </object>
  </html>

Education
======
* M.S. in USA, Duke University, 2021
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
