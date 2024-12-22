---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}



<script>
    function pressBtn(p) {

      var id_btn=["exp-btn", "pub-btn"], class_btn=["fas fa-plus-square", "fas fa-minus-square"];
      var id_div=["exp-div", "pub-div"], style_div=["height: 300px; overflow: auto;", "height: 400px; overflow: auto;"];

      var btn = document.getElementById(id_btn[p]);
      if(btn.className == class_btn[0]) {
        btn.className = class_btn[1];
        document.getElementById(id_div[p]).style = "";
      }
      else {
        btn.className = class_btn[0];
        document.getElementById(id_div[p]).style = style_div[p];
      }
    }

    function img_hover(e, f) {
      e.setAttribute("src", f);
    }
    function img_unhover(e, f) {
      e.setAttribute("src", f);
    }
</script>



Education
======
* M.S. in Computer Science, Georgia Institute of Technology, 2024
  + <span style="font-size: 0.75em">GPA: 3.8/4.0</span>
  + <span style="font-size: 0.75em">Related courses: Reinforcement Learning, Deep Learning, Machine Learning, Artificial Intelligence, AI for Robotics, Game AI, Ethics in AI, Data & Visual Analytics, Graduate Algorithms</span>
   
* B.E. in Electronics and Telecommunication, Army Institute of Technology (SPPU), India, 2017
  + <span style="font-size: 0.75em">GPA: 3.561/4.0, (AGIF Scholarship Recipient)</span>
  + <span style="font-size: 0.75em">Related courses: Soft Computing, Internet of things, Information Theory, System Programming and Microcontrollers</span>


<!-- adding td
td {
  padding: 0px 20px 0px 20px;
  vertical-align: middle;
}
td.all {
  width: 100%;
}
td.exp-avatar {
  width: 15%;
}
td.exp-description {
  width: 80%;
}
td.pub-avatar {
  width: 30%;
}
td.pub-description {
  width: 65%;
}--> 







Work experience
======
<div style="height: 300px; overflow: auto;" id="exp-div">
  <table><tbody>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="https://www.isb.edu/content/dam/sites/diri/logo.png" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 20%;">
      <b>Research Associate</b>
      <span style="float: right;">Feb. 2023 - present</span>
      <br>
      <a href="www.isb.edu" target="_blank">Indian School of Business</a>
      <br>
      Advisor: <a href="https://www.isb.edu/en/research-thought-leadership/faculty/faculty-directory/vandith-pamuru.html">Dr. Vandith Pamuru</a>
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 60%;">
      Designed & documented research studies, created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, hired & supervised 3 interns.
      </td>
    </tr>
  </tbody></table>
</div>





  

* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
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
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
