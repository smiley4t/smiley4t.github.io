---
layout: default
title: Projects
permalink: /projects/
---



This page showcases selected projects where I apply **data science, data analysis, visualization, and storytelling** to real-world problems.  
Each project focuses not only on tools, but also on **how data is transformed into insights**.

---


## All Projects

<style>
/* Accordion container */
.proj-acc details{
  background:#fff; border:1px solid #eee; border-radius:14px;
  padding:14px 18px; margin:14px 0;
  box-shadow:0 6px 20px rgba(0,0,0,0.04);
}
.proj-acc summary{
  cursor:pointer; font-size:1.25rem; font-weight:800;
  list-style:none; display:flex; align-items:center; justify-content:space-between;
}
.proj-acc summary::-webkit-details-marker{ display:none; }
.proj-acc .chev{ font-size:1.2rem; opacity:.7; }
.proj-acc details[open] .chev{ transform:rotate(180deg); }
.proj-acc .content{ margin-top:14px; padding-top:12px; border-top:1px solid #f0f0f0; }

/* Project card */
.project-card{
  display:flex; gap:14px; align-items:flex-start;
  border:1px solid #f0f0f0; border-radius:14px;
  padding:14px; margin:14px 0;
}
.project-thumb{
  width:160px; height:110px; flex:0 0 160px;
  object-fit:cover; border-radius:12px; border:1px solid #ddd;
}
.project-body{ flex:1; }
.project-title{ margin:0 0 6px 0; font-size:1.05rem; font-weight:800; }
.project-links{ margin:6px 0 0 0; }
.project-summary{ margin:0 0 10px 0; opacity:.88; }

/* Skill tags */
.tags{ display:flex; flex-wrap:wrap; gap:8px; margin:0; padding:0; list-style:none; }
.tags li{
  display:inline-block; padding:4px 10px;
  border:1px solid #e6e6e6; border-radius:999px;
  font-size:.88rem; opacity:.95;
}

/* Mobile responsive */
@media (max-width: 650px){
  .project-card{ flex-direction:column; }
  .project-thumb{ width:100%; height:180px; flex:auto; }
}
</style>

<div class="proj-acc">

<details open>
  <summary>AI project <span class="chev">▼</span></summary>
  <div class="content">

    <!-- Project Card -->
    <div class="project-card">
      <img class="project-thumb"
           src="/medical_misinfo.jpg"
           alt="Medical info thumbnail">

      <div class="project-body">
        <h4 class="project-title"> Fine-tuning LLM model for Medical Misinformation detection </h4>

        <p class="project-summary">
        Reloading Llama-13B-2 model from Hugging Face and fine-tuning the model on three datasets for medical misinformation detection, creating a chatbot for response generation
       
        </p>

        <ul class="tags">
          <li>LLM Fine-Tuning</li>
          <li>Natural Language Processing</li>
          <li>Parameter-Efficient Fine-Tuning</li>
          <li>Hugging Face Transformers</li>
          <li>RAG</li>
        </ul>

        <p class="project-links">
          🔗 <b>Github:</b> 
          <a href="https://github.com/DataBytes-Organisation/Fine-Tuning-LLMs-for-Enterprise-Applications/tree/alissa_branch"
         target="_blank" rel="noopener">
         Link project
      </a>
        </p>
      </div>
    </div>
    <!-- End Project Card -->
    </div>
    
</details>
<details>
  <summary>Data visualization <span class="chev">▼</span></summary>
  <div class="content">

    <!-- Project Card -->
    <div class="project-card">
      <img class="project-thumb"
           src="/GDP analysis.png"
           alt="Global GDP Analysis Dashboard thumbnail">

      <div class="project-body">
        <h4 class="project-title"> Global GDP Analysis Dashboard (1995–2024)</h4>

        <p class="project-summary">
          Built an interactive Tableau dashboard to compare GDP levels, average growth, and regional share of world GDP to surface long-term trends and emerging economies.
        </p>

        <ul class="tags">
          <li>Tableau</li>
          <li>Dashboard Design</li>
          <li>Data Storytelling</li>
          <li>Trend Analysis</li>
          <li>Excel</li>
        </ul>

        <p class="project-links">
          🔗 <b>Tableau Public:</b> 
          <a href="https://public.tableau.com/views/GlobalGDPAnalysisDashboard/Dashboard2?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"
         target="_blank" rel="noopener">
         View Dashboard
      </a>
        </p>
      </div>
    </div>
    <!-- End Project Card -->
    <!-- Project Card -->
<div class="project-card">
  <img class="project-thumb"
       src="/Colac.jpg"
       alt="Colac Otway and Greater Geelong Dashboard thumbnail">

  <div class="project-body">
    <h4 class="project-title"> Colac Otway & Greater Geelong – Immigration Analysis</h4>

    <p class="project-summary">
      Volunteered on a regional research project analyzing immigration patterns in Colac Otway and Greater Geelong using Australian Bureau of Statistics data.
    </p>

    <ul class="tags">
      <li>Tableau</li>
      <li>Data Cleaning</li>
      <li>Demographic Analysis</li>
      <li>Data Visualization</li>
      <li>Excel</li>
    </ul>

    <p class="project-links">
      🔗 <b>Tableau Public:</b>
      <a href="https://public.tableau.com/views/Colac-Geelong/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"
         target="_blank" rel="noopener">
         View Dashboard
      </a>
    </p>
  </div>
</div>
<!-- End Project Card -->

  </div>
</details>

<details>
  <summary>Machine Learning and Data Science Projects <span class="chev">▼</span></summary>
  <div class="content">

    <div class="project-card">
      <img class="project-thumb"
           src="/patient.jpg"
           alt="Neural Network thumbnail">

      <div class="project-body">
        <h4 class="project-title"> Classification of patient's diagnosis with Neural Network </h4>

        <p class="project-summary">
          Using Neural Network to classify pediatric patients with abdominal pain into two groups : appendicitus and no appendicitus
        </p>

        <ul class="tags">
          <li>Python</li>
          <li>Pandas</li>
          <li>Data Cleaning</li>
          <li>Seaborn</li>
          <li>Feature Engineering</li>
        </ul>

        <p class="project-links">
          🔗 <b>GitHub:</b> 
           <a href="https://github.com/smiley4t/Neural-Network.git"
         target="_blank" rel="noopener">
         Link project
      </a>
        </p>
      </div>
    </div>
    <!-- End Project Card -->
     <!-- Project Card -->
<div class="project-card">
  <img class="project-thumb"
       src="/waste classification.jpg"
       alt="Images classification thumbnail">

  <div class="project-body">
    <h4 class="project-title"> Classification of images with Convolutional Neural Network</h4>

    <p class="project-summary">
    Using Convolutional Neural Network to capture spatial features of increasing levels of abstraction of images of rubbish and classify them into different types of rubbish for recycling
    </p>

    <ul class="tags">
      <li>Scikit Learn</li>
      <li>Data Cleaning</li>
      <li>Data Augmentation</li>
      <li>Data Visualization</li>
      <li>Convolutional Neura Network</li>
    </ul>

    <p class="project-links">
      🔗 <b>Github:</b>
      <a href="https://github.com/smiley4t/Convolutional_Neural_Network.git"
         target="_blank" rel="noopener">
        Link project
      </a>
    </p>
  </div>
</div>
<!-- End Project Card -->

  </div>





