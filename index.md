---
layout: default
title: Sean Liu
---

## Hello World
Hi, I’m Sean, an M.S. Computer Science student at Georgia Tech, on track to graduate in December 2025, specializing in machine learning. I earned my bachelor’s degree in Computer Science from Georgia Tech in May 2024, with concentrations in artificial intelligence and information internetworks, along with a minor in economics. I’m excited to leverage cutting-edge technology to build innovative, real-world solutions.

<a id="about"></a>
## About Me
[Feel free to connect with me on LinkedIn](https://www.linkedin.com/in/sliu750)

[My Resume](Sean_Liu_Resume_F25.pdf)

## Experiences

<div class="timeline">

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/schwab.png" alt="Charles Schwab Logo" class="timeline-logo" />
      <div>
        <h3>Charles Schwab</h3>
        <p>Software Engineering Intern<br>June 2025 – August 2025</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Model Risk Oversight department</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/fsil.jpg" alt="FSIL Logo" class="timeline-logo" />
      <div>
        <h3>Georgia Tech Financial Services Innovation Lab</h3>
        <p>Graduate Research Assistant<br>August 2024 – June 2025</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Create tools leveraging artificial intelligence to support financial and economic decision-making</li>
        <li>Serve as a liaison between the professor, research staff, and interns, facilitating collaboration and communication</li>
        <li>Supervise 20 research interns, providing technical guidance in data curation, coding, and model and application development</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/fsil.jpg" alt="FSIL Logo" class="timeline-logo" />
      <div>
        <h3>Georgia Tech Financial Services Innovation Lab</h3>
        <p>Volunteer Research Assistant<br>May 2024 – August 2024</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Conducted multidisciplinary research between Georgia Tech's College of Computing and College of Business</li>
        <li>Analyzed the decision-making and predictive abilities of large language models in financial contexts</li>
        <li>Wrote Python scripts to aggregate financial data and legislation, contributing to training a financial large language model</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/vip.jpg" alt="VIP Logo" class="timeline-logo" />
      <div>
        <h3>Vertically Integrated Project</h3>
        <p>Researcher<br>August 2022 – December 2023</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Collaborated on the Autonomous and Connected Transportation (ACT) Driving Simulator, a faculty-led multidisciplinary project</li>
        <li>Designed innovative transportation solutions, focusing on accessibility and sustainability in smart cities</li>
        <li>Created machine learning models in Python to detect driver distraction and predict driver behavior from physiological data, achieving over 80% test accuracy and enhancing road safety</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/alphamodels.png" alt="Alpha Models Logo" class="timeline-logo" />
      <div>
        <h3>Alpha Models Inc.</h3>
        <p>Software Engineering Intern<br>May 2023 – August 2023</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Developed a C++ simulation model for railcar shipments using constrained shortest path algorithm</li>
        <li>Implemented Java algorithms to solve the Vehicle Routing Problem for planning and scheduling freight railroad maintenance</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/logos/alphamodels.png" alt="Alpha Models Logo" class="timeline-logo" />
      <div>
        <h3>Alpha Models Inc.</h3>
        <p>Software Engineering Intern<br>May 2022 – August 2022</p>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Studied business policies, operational constraints, and government regulations in the railroad transportation industry</li>
        <li>Analyzed industrial transportation data to evaluate economic performance and regulation appliance</li>
        <li>Created C++ optimization models using graph algorithms to determine the most efficient rail routes</li>
      </ul>
    </div>
  </div>

</div>

<script>
function toggleDetails(item) {
  const details = item.querySelector(".timeline-details");
  if (details.style.maxHeight) {
    details.style.maxHeight = null;
    details.style.opacity = 0;
  } else {
    details.style.maxHeight = details.scrollHeight + "px";
    details.style.opacity = 1;
  }
}
</script>

## Projects

<div class="timeline">

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/images/agriculture.jpg" alt="Data Vis Logo" class="timeline-logo" />
      <div>
        <h3>Environmental Impacts of Agriculture</h3>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Created <a href="https://syoon029.github.io/6730-Data-Vis-Team-Project.github.io/" target="_blank">interactive visualizations</a> with Tableau, explaning how agriculture impacts greenhouse gas emissions, biodiversity, and energy and water consumption</li>
        <li>Produced interactive visualizations with Tableau, displaying trends across the world over the years</li>
        <li>Highlighted main agricultural contributors of environmental challenges, comparing the losses to the outputs</li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/images/urban_forest.jpg" alt="Treehuggers Logo" class="timeline-logo" />
      <div>
        <h3>Machine Learning Powered Analysis of Urban Forests</h3>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Applied machine learning models (e.g. random forest and gradient boosting classifiers and regressors) and deep learning models (e.g. neural networks) to predict the conditions of urban trees and their impact on public health, particularly in Los Angeles</li>
        <li>Created interactive visualizations displaying the status and diversity of trees around the United States</li>
        <li><a href="team004poster.pdf" target="_blank">Poster</a> and <a href="https://github.com/sliu750/CSE-6242-Team-Project" target="_blank">GitHub repo</a></li>
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/images/realestate.jpg" alt="Real Estate Logo" class="timeline-logo" />
      <div>
        <h3>Data Science for Real Estate</h3>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        <li>Implemented supervised machine learning models (decision tree, regression) to predict whether someone should rent a house and to estimate the price of a house based on its characteristics</li>
        <li>Applied unsupervised methods (clustering) to group houses by similar features, helping sellers determine a suitable price range</li>
        <li><a href="https://github.com/sliu750/ML4641-Team-Project" target="_blank">GitHub repo</a></li>
        
      </ul>
    </div>
  </div>

  <div class="timeline-item" onclick="toggleDetails(this)">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
      <img src="assets/images/stocks.jpg" alt="Financial Text Logo" class="timeline-logo" />
      <div>
        <h3>Company Performance Prediction from Financial Texts with NLP</h3>
      </div>
    </div>
    <div class="timeline-details">
      <ul>
        
        <li>Employed nltk and Python's transformers packages to extract key information from Big Tech companies' financial reports</li>
        <li>Classified strongly sentimental sentences as either positive or negative and visualized and predicted such trends over time, providing users with a holistic view of a company's performance from the management's perspective</li>
        <li>Deployed <a href="https://fintech-assignment.streamlit.app/" target="_blank">web application</a> using Streamlit</li>
      </ul>
    </div>
  </div>

</div>

## Skills
Throughout my courses and self-studying, I have gained proficiency in a variety of programming languages, frameworks, and libraries.

<div class="skills-grid">
  <div class="skill"><img src="assets/icons/python.png" alt="Python" /><span>Python</span></div>
  <div class="skill"><img src="assets/icons/java.svg" alt="Java" /><span>Java</span></div>
  <div class="skill"><img src="assets/icons/C.svg" alt="C" /><span>C</span></div>
  <div class="skill"><img src="assets/icons/cpp.svg" alt="C++" /><span>C++</span></div>
  <div class="skill"><img src="assets/icons/csharp.svg" alt="C#" /><span>C#</span></div>
  <div class="skill"><img src="assets/icons/mysql.svg" alt="MySQL" /><span>MySQL</span></div>
  <div class="skill"><img src="assets/icons/js.png" alt="JavaScript" /><span>JavaScript</span></div>
  <div class="skill"><img src="assets/icons/R.png" alt="R" /><span>R</span></div>
  <div class="skill"><img src="assets/icons/matlab.png" alt="MATLAB" /><span>MATLAB</span></div>
  <div class="skill"><img src="assets/icons/go.png" alt="Go" /><span>Go</span></div>
  <div class="skill"><img src="assets/icons/aws.png" alt="AWS" /><span>AWS</span></div>
  <div class="skill"><img src="assets/icons/tableau.png" alt="Tableau" /><span>Tableau</span></div>
  <div class="skill"><img src="assets/icons/numpy.png" alt="Numpy" /><span>NumPy</span></div>
  <div class="skill"><img src="assets/icons/sklearn.png" alt="sklearn" /><span>sklearn</span></div>
  <div class="skill"><img src="assets/icons/pytorch.png" alt="pytorch" /><span>PyTorch</span></div>
  <div class="skill"><img src="assets/icons/tensorflow.png" alt="tensorflow" /><span>TensorFlow</span></div>
  <div class="skill"><img src="assets/icons/git.svg" alt="git" /><span>Git</span></div>
</div>

## Hobbies
Outside of work and studies, I enjoy hitting the gym, experimenting with new recipes in the kitchen, and diving into the latest breakthroughs in AI/ML, history, and the sciences. I love exploring the city I’m in, spending time with friends, and unwinding with some good entertainment- especially We Bare Bears or Calvin and Hobbes.
<style>
.skills-grid {
  display: grid;
  grid-template-columns: repeat(5, 1fr); 
  gap: 20px;
  margin-top: 1em;
  margin-bottom: 3em;
}

.skill {
  display: flex;
  align-items: center;
  justify-content: flex-start; 
  flex-wrap: wrap;
  gap: 10px;
  padding: 8px 10px;
  border: 1px solid #ddd;
  border-radius: 8px;
  background-color: #f9f9f9;
  font-size: 0.95rem;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  min-width: 0;
  word-break: break-word;
  text-align: center;
}

.skill img {
  width: 22px;
  height: 22px;
  object-fit: contain;
}

.skill span {
  white-space: nowrap;
  font-size: 0.9rem;
}
</style>

<style>
.timeline {
  position: relative;
  margin: 2em 0;
  padding-left: 30px;
  border-left: 3px solid #ccc;
}

.timeline-item {
  position: relative;
  margin-bottom: 30px;
}

.timeline-content {
  background: #f9f9f9;
  padding: 10px 15px;
  border-radius: 6px;
  box-shadow: 0 1px 3px rgba(0,0,0,0.05);
  display: flex;
  align-items: center;
  gap: 15px;
}

.timeline-logo {
  width: 65px;
  height: 65px;
  object-fit: contain;
  margin-right: 1rem;
}

.timeline-content h3 {
  margin: 0 0 5px;
  font-size: 1.1rem;
}

.timeline-content p {
  margin: 0;
  font-size: 0.95rem;
}

.timeline-details {
  overflow: hidden;
  max-height: 0;
  opacity: 0;
  transition: all 0.3s ease;
  margin-top: 10px;
  padding-left: 80px;
}

.timeline-details ul {
  margin: 0;
  padding-left: 20px;
  list-style-type: disc;
  color: #333;
  font-size: 0.9rem;
}

.site-header .wrapper > p {
    display: none;
  }
</style>
