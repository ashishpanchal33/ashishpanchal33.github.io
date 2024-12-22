---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download [Academic CV](/files/CV_Ashish_Panchal_acad.pdf) or [Professional CV (last updated Dec 23)](/files/CV_Ashish_Panchal_prof.pdf)

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
* [M.S. in Computer Science](https://www.parchment.com/u/award/faa1551a16ea5402915eda6d54efa156), Georgia Institute of Technology, 2024
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
      Designed & documented research studies, and created IRB transcripts. 
      Designed models and ran real-life & simulated experiments. Performed literature review, and Analysis. Additionally, I hired & supervised 3 interns.
      <br>
      I focused on adaptive decision-making in complex social situations. My work includes developing A2C-DT, a novel reinforcement learning model demonstrating an 86% win rate in strategic game environments, resulting in an AAMAS 2025 submission. I'm also conducting an empirical study using real-world business data, targeting IJOC, and a VR-based human negotiation study, targeting JOB
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
      I designed and deployed data science solutions to understand and mitigate risk in the Indian credit market, focusing on improving lending policies and customer service.
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
      I translated business needs into analytical solutions, leading the development of end-to-end pipelines & improving existing models.  I hired & supervised the data science team.
      </td>
    </tr>
    <tr>
      <td style=";padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;" bgcolor="black">
      <img src="https://www2.deloitte.com/content/dam/assets/logos/deloitte.svg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 25%;">
      <b>Business Technology Analyst</b>
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
      My work focused on developing and implementing data-driven solutions. For a major gaming company, I performed extensive performance analysis, leveraging key metrics and event logs to assess availability, reliability, and performance.
      </td>
    </tr>

    
  </tbody></table>
</div>

  
Skills
======
* **Programming languages**:  Python, C#, R, Cuda
* **Programming Tools and Libraries**:
  * **Reinforcement Learning and Deep Learning**: Transformers(Huggingface), Stable-Baselines3, ClearnRL, Pytorch, Tensorboard, Pettingzoo, Gymnasium(OpenAI Gym) 
  * **Machine learning and Data Science toolkit**:  NLTK, Scikit-learn, SciPy, NumPy, Pandas, Sparks, Pyarrow, fastparquet
  * **Visualization Toolkit**: Matplotlib, Seaborn, Plotly, Dash(Plotly), Tableau
  * **App design**: Dash(Plotly), Flask
  * Misc : Selenium
* **Solution Design Experience**: Credit Risk Modeling, Social listening analysis, Fraud detection(fuzzy logic), Sales Forecasting, Market Mix Modeling, Demand forecasting, Attribution Modeling, Analytics Pipeline Design.
* **Research Experience**: Literature review, Research Study and Experiment Design, Statistical Analysis, Meta-Analysis, IRB transcript and Project report writing.
* **Management**: Project and Task planning, Call and Client management, Team management.

Projects and Publications
======

Please refer [Projects and Publications](/publications/) page.

<!--- <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> 
--->

  
Social Responsibility
======
* NGO Volunteer - Environmental Synergies in Development (ENSYDE): Promoted e-waste awareness through booths at various conventions. (2017-present)
* NGO Volunteer - Youth for Seva (YFS): Volunteered with YFS teaching children at government schools. (2018-present)
* NGO Volunteer -  Youth For Parivarthan: Led community-driven initiatives to clean & revitalize public areas (2018-2022)

Academic Volunteering and Coordination
======
* WITS conference volunteer (ISB): Event coordination and assistance. [Tracks: 1. ML/AI, 2. DEI, 3. Recommender systems] (2023)
* WISE conference volunteer (ISB): Track coordinator [ 1. Platforms and Misinformation, 2. AI and governance] (2023)
* Nvidia Lab Coordinator (AIT): Coordinated Nvidia CUDA programming workshops for students along, and Collaborated with Industry professionals  (2015)

Military Experience
======
<div style=" overflow: auto;" id="exp-div">  
  <table><tbody>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="/images/NDA.jpeg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 80%;">
      <span style="float: right;">Jul. 2013 - Jul 2014</span>
      <br>
     Academics and Military Training at the prestigious National Defence Academy (India)
      </td>
    </tr>
  </tbody>
  </table>
</div>


Honors, prizes, awards, and fellowships:
======
* Project selected for CreateX startup lab, Georgia Institute of Technology (2022)
* Star of the Quarter, Quantzig, Awarded by HOD for exceptional project delivery (2020)
* Super Star Award, Quantzig, Awarded by VP for exceptional yearly contribution (2020)
* Spot Award, Deloitte USI, Awarded by HOD (2019)
* Recommended for Officers Training Academy (Indian Army - Engg.) All-India-Rank: 13 (2018)
* AGIF Scholarship (Award for academic excellence), Army Institute of Technology, (2015)
* Recommended for National Defence Academy(Indian Army) All-India-Rank: 107 (of ~ 400,000 applicants) (2013)

Teaching:
======
* Designed a course and taught Machine Learning, Data Science, and Python programming to new joinees at MoneyView (2021-2023)
* Mentored second and third-year Bachelor of Engineering students on the practical implementation of industry-relevant projects (2014-2016)

Selected Certifications:
======
* Probability - The Science of Uncertainty and Data (2020) – MITx on Edx
* Fundamentals of Statistics (2020) – MITx on Edx
* Data Analysis in Social Science(2020) – MITx on Edx
* Machine Learning with Python-From Linear Models to Deep Learning (2020) – MITx on Edx (MIT 18.650)


