---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
  table{
    width: auto;
    border: none;
  }
  
  th {
    font-size: 30px;
  }
  
  td{
    padding: 1.5em;
  }
  
  td, th {
    border: none;
  }
  
  img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 120px;
    min-width: 45px;
    height: auto;
  }
</style>

{% include base_path %}

<table>
  <tr>
    <th colspan=2> Education </th>
  </tr>
  <tr>
    <td><a href="https://www.ece.ntua.gr/en" target="_blank"><img src="../images/pyrforos.png"></a></td>
    <td><b>National Technical University of Athens</b> <br/>
      <i>B.Sc - M.Eng</i> in <i>Electrical & Computer Engineering</i> <br/>
      2015 - 2021  <br/>
      <i>Major</i>: Computer Science <br/>
      <i>GPA</i>: 8.11 / 10.00 <br/>
      <i>Thesis</i>: "Focused Crawling on ethnopharmacological topics with Active and Reinforcement Learning" <br/>
      <i>Advisors</i>: <a href="https://users.iit.demokritos.gr/~ggianna/" target="_blank">Dr. George Giannakopoulos</a>, <a             href="https://slp.cs.ece.ntua.gr/potam/index.html" target="_blank">Prof. Alexandros Potamianos</a>
    </td>
  </tr>
</table>

<hr>

<table>
  <tr>
    <th colspan=2> Research Experience </th>
  </tr>
  <tr>
    <td><a href="http://datacron1.ds.unipi.gr:9083/ai-lab/" target="_blank"><img src="../images/UNIPI.jpg"></a></td>
    <td><b>University of Pireaus</b>, Artificial Intelligence Laboratory, Greece <br/>
      Jun 2021 - Present: <i><b>Research Assistant</b></i> <br/>
      <i><u>Research topics</u></i>: Explainable Reinforcement Learning (XRL) <br/>
      - Working on <a href="http://datacron1.ds.unipi.gr:9083/ai-lab/projects/tapas-towards-an-automated-and-explainable-atm-system/" target="_blank">TAPAS</a> project <br>
      - Supervised by <a href="https://www.semanticscholar.org/author/G.-Vouros/1680125" target="_blank">Prof. George Vouros</a>
    </td>
  </tr>
    <tr>
    <td><a href="https://www.iit.demokritos.gr/" target="_blank"><img src="../images/demokritos-ncsr-logo.png"></a></td>
    <td><b>National Center for Scientific Research "Demokritos"</b>, Software and Knowledge Engineering Lab, Greece <br/>
      Mar 2020 - Feb 2021: <i><b>Undergraduate Research Assistant</b></i> <br/>
      <i><u>Research topics</u></i>: Focused Crawling tasks with Reinforcement Learning (RL) <br/>
      - Supervised by <a href="https://users.iit.demokritos.gr/~ggianna/" target="_blank">Dr. George Giannakopoulos</a>
    </td>
  </tr>
</table>

<hr>

<table>
  <tr>
    <th colspan=2> Teaching Experience </th>
  </tr>
  <tr>
    <td><a href="https://www.ece.ntua.gr/en" target="_blank"><img src="../images/pyrforos.png"></a></td>
    <td><b>National Technical University of Athens</b>, School of ECE, Greece <br/>
      Oct 2016 - Feb 2019: <i><b>Undergraduate Teaching Assistant</b></i> <br/>
      <i><u>Courses</u></i>: 
      <a href="https://www.ece.ntua.gr/en/undergraduate/courses/3020" target="_blank">Computer Programming</a> (3.4.3020.1), 
      <a href="https://www.ece.ntua.gr/en/undergraduate/courses/3138" target="_blank">Programming Techniques</a> (3.4.3138.2)
    </td>
  </tr>
</table>


<hr>
<table>
  <tr><th> Publications </th></tr>
   {% for post in site.publications %}
    <tr><td>{% include archive-single-cv.html %}</td></tr>
  {% endfor %}
</table>
<hr>

<hr>
<table>
  <tr><th> Talks and Presentations </th></tr>
   {% for post in site.talks %}
    <tr><td>{% include archive-single-cv.html %}</td></tr>
  {% endfor %}
</table>
<hr>

Skills
------
* Programming Languages: Python, Java, Prolog, C/C++, SML, SQL
* Machine Learning: Tensorflow, Keras, Sklearn

Languages
------
🇬🇷 Greek (Native), 🇬🇧 🇺🇸 English (C2), 🇩🇪 German (B1)

Hobbies
-------
Football ⚽, Basketball 🏀, AI Books 🚀, Movies 🎥
