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
      <i>GPA</i>: 8.1 / 10 <br/>
      <i>Thesis</i>: "Focused Crawling on ethnopharmacological topics with Active and Reinforcement Learning" <br/>
      <i>Advisors</i>: <a href="https://users.iit.demokritos.gr/~ggianna/" target="_blank">George Giannakopoulos</a>, <a             href="https://slp.cs.ece.ntua.gr/potam/index.html" target="_blank">Prof. Alexandros Potamianos</a>
    </td>
  </tr>
</table>

<hr>

<table>
  <tr>
    <th colspan=2> Research Experience </th>
  </tr>
  <tr>
    <td><a href="https://www.iit.demokritos.gr/" target="_blank"><img src="../images/demokritos-ncsr-logo.png"></a></td>
    <td><b>National Center for Scientific Research "Demokritos"</b>, Agia Paraskevi, Greece <br/>
      Mar 2020 - Present: <i>Undergraduate Research Assistant</i> at the <i>Institute of Informatics & Telecommunications</i> <br/>
      Jul 2020 - Aug 2020: <i>Research intern</i> at the <i>Institute of Informatics & Telecommunications</i> <br/>
      <i>Duties</i>: Focused Crawling Tasks with Reinforcement Learning <br/>
    </td>
  </tr>
</table>

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
* Machine Learning: Tensorflow 2.x, Keras, Sklearn, PyTorch

Languages
------
🇬🇷 Greek (Native), 🇬🇧 🇺🇸 English (C2), 🇩🇪 German (B1)

Hobbies
-------
Football ⚽, Basketball 🏀, AI Books 🚀, Movies 🎥
