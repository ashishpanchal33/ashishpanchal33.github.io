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
<!--- <div style="height: 600px; overflow: auto;" id="exp-div"> --->
<div style=" overflow: auto;" id="exp-div">  
  <table><tbody>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="https://www.isb.edu/content/dam/sites/diri/logo.png" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 25%;">
      <b>Research Associate</b>
      <br>
      <a href="www.isb.edu" target="_blank">Indian School of Business</a>
      <br>
      Advisor: <a href="https://www.isb.edu/en/research-thought-leadership/faculty/faculty-directory/vandith-pamuru.html">Dr. Vandith Pamuru</a>
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 55%;">
      <span style="float: right;">Feb. 2023 - present</span>
      <br>
      Designed & documented research studies, created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, hired & supervised 3 interns.
      </td>
    </tr>
    <br>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="https://moneyview.in/images/mv-green-logo-v3Compressed.svg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 25%;">
      <b>Senior Data Scientist</b>
      <br>
      <a href="https://moneyview.in/" target="_blank">MoneyView</a>
      <br>
      Manager: <a href="https://in.linkedin.com/in/antony-cherian-66500515">Antony Cherian</a>
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 55%;">
      <span style="float: right;">Nov. 2021 - Feb. 2023</span>
      <br>
      Designed & documented research studies, created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, hired & supervised 3 interns.
      </td>
    </tr>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="https://www.quantzig.com/wp-content/uploads/2024/08/quantzig-logo.svg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 25%;">
      <b>Senior Analytics Consultant</b>
      <br>
      Data Science Team lead
      <br>
      <a href="https://www.quantzig.com/" target="_blank">Quantzig</a>
      <br>
      Manager: <a href="https://in.linkedin.com/in/lalithvelamuri">Lalith Velamuri</a>
      <br>
      Senior-Manager: <a href="https://in.linkedin.com/in/sudarshankl">Sudarshan KL</a>
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 55%;">
      <span style="float: right;">Jul. 2019 - Nov. 2021</span>
      <br>
      Designed & documented research studies, created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, hired & supervised 3 interns.
      </td>
    </tr>
    <tr>
      <td style="bgcolor:black;padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="https://www2.deloitte.com/content/dam/assets/logos/deloitte.svg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 25%;">
      <b></b>
      <br>
      <a href="https://www2.deloitte.com/us/en.html" target="_blank">Deloitte US-India</a>
      <br>
      Manager: <a href="https://in.linkedin.com/in/hema-chikkanna-b53b48aa">Hema Chikkanna</a>
      <br>
      SVP: <a href="https://www.linkedin.com/in/vcbiju">Biju Chacko</a>
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 55%;">
      <span style="float: right;">Jun. 2017 - Jul. 2019</span>
      <br>
      Designed & documented research studies, created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, hired & supervised 3 interns.
      </td>
    </tr>






    
  </tbody></table>
</div>

  
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

  
Service and leadership
======
* Currently signed in to 43 different slack teams
