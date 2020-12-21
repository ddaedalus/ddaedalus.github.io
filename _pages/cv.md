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
<!--       <i>Thesis</i>: <a href="https://dspace.lib.ntua.gr/xmlui/bitstream/handle/123456789/52318/chochlakis_thesis.pdf?sequence=4&isAllowed=y" target="_blank"> Using Artificial Neural Networks for Zero-shot Learning </a> <br/> -->
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
      <i>Research intern</i> at the <i>Institute of Informatics & Telecommunications</i> <br/>
      Jul 202o - Aug 2020 <br/>
      <i>Duties</i>: Focused Crawling Tasks with Reinforcement Learning <br/>
<!--       <i>Body of Work</i>: <a href="https://www.mdpi.com/2072-4292/12/12/2002" target="_blank">paper</a> with <a href="https://github.com/Panagiotou/ImageToDEM" target="_blank">code</a> <br/> -->
<!--       <i>Advisor</i>: <a href="https://users.iit.demokritos.gr/~exarou/" target="_blank">Dr. Eleni Charou</a> -->
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
