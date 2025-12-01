---
layout: page
title: My Projects
subtitle: Analytical, Technical & Business Projects
featured-on-home: true
description: Explore my portfolio of projects spanning business analytics, engineering simulations, and strategic analysis.
thumbnail-img: "/assets/img/tnail_1.png"
---

<style>
.projects-header {
  text-align: center;
  max-width: 800px;
  margin: 0 auto 3rem;
}

.projects-grid {
  display: grid;
  gap: 2rem;
  margin: 2rem 0;
}

.project-card {
  background: white;
  border-radius: 1rem;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border: 2px solid #E2E8F0;
  display: grid;
  grid-template-columns: 350px 1fr;
  gap: 0;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 20px 25px rgba(0, 0, 0, 0.15);
  border-color: #667EEA;
}

.project-image {
  overflow: hidden;
  position: relative;
  height: 100%;
  min-height: 250px;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.5s ease;
}

.project-card:hover .project-image img {
  transform: scale(1.1);
}

.project-content {
  padding: 2rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.project-number {
  display: inline-block;
  background: linear-gradient(135deg, #667EEA 0%, #764BA2 100%);
  color: white;
  padding: 0.25rem 0.75rem;
  border-radius: 1rem;
  font-size: 0.875rem;
  font-weight: 600;
  margin-bottom: 0.75rem;
}

.project-title {
  font-size: 1.5rem;
  color: #1A202C;
  margin-bottom: 1rem;
  font-weight: 700;
  line-height: 1.3;
}

.project-description {
  color: #4A5568;
  line-height: 1.8;
  margin-bottom: 1.5rem;
  flex-grow: 1;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-bottom: 1rem;
}

.project-tag {
  background: #EDF2F7;
  color: #4A5568;
  padding: 0.375rem 0.75rem;
  border-radius: 0.5rem;
  font-size: 0.8125rem;
  font-weight: 500;
}

.project-link {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  color: #667EEA;
  font-weight: 600;
  text-decoration: none;
  transition: all 0.2s ease;
}

.project-link:hover {
  color: #5A67D8;
  transform: translateX(5px);
}

.project-link::after {
  content: '→';
  font-size: 1.25rem;
}

@media (max-width: 768px) {
  .project-card {
    grid-template-columns: 1fr;
  }
  
  .project-image {
    min-height: 200px;
  }
}
</style>

<div class="projects-header">
  <h2 style="font-size: 2.5rem; margin-bottom: 1rem;">Featured Projects</h2>
  <p style="font-size: 1.125rem; color: #4A5568; line-height: 1.8;">
    A collection of my academic, professional, and analytical projects demonstrating expertise in business intelligence, engineering simulation, and strategic analysis.
  </p>
</div>

<div class="projects-grid">

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/drive/folders/1JX4vxVmLHawc6d335NAPNy5jrZ5mIUHb?usp=sharing" target="_blank">
        <img src="/assets/img/tnail_1.png" alt="Sales Analytics Dashboard" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 01</span>
        <h3 class="project-title">Sales Analytics PowerBI Dashboard for Global Electronics Retailers</h3>
        <div class="project-tags">
          <span class="project-tag">Power BI</span>
          <span class="project-tag">Data Analytics</span>
          <span class="project-tag">Business Intelligence</span>
        </div>
        <p class="project-description">
          Developed an interactive Power BI dashboard to analyze global electronics retail sales, integrating six extensive datasets to visualize key metrics like revenue, profit, and regional sales trends. Enabled strategic financial insights by tracking profitability, cost distribution, and market performance across brands, product categories, and countries to support data-driven business decisions.
        </p>
      </div>
      <a href="https://drive.google.com/drive/folders/1JX4vxVmLHawc6d335NAPNy5jrZ5mIUHb?usp=sharing" target="_blank" class="project-link">
        View Project
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://github.com/dhruvi-sisodiya/business_intelligence-AI_chatbot_disclosure" target="_blank">
        <img src="/assets/img/tnail1.png" alt="AI Chatbot Analysis" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 02</span>
        <h3 class="project-title">AI Chatbot Disclosure and Customer Behavior Analysis</h3>
        <div class="project-tags">
          <span class="project-tag">SQL</span>
          <span class="project-tag">Python</span>
          <span class="project-tag">Statistical Analysis</span>
        </div>
        <p class="project-description">
          Studied an experimental dataset using SQL, Python, and Gretl to analyze AI chatbot disclosure effects on customer behavior. Extracted insights showing financial attributes influence purchase behavior more than call dynamics. Delivered analytical workflows and visualizations to support data-driven business strategy.
        </p>
      </div>
      <a href="https://github.com/dhruvi-sisodiya/business_intelligence-AI_chatbot_disclosure" target="_blank" class="project-link">
        View on GitHub
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://docs.google.com/spreadsheets/d/1PRsDHUQzEJgM6h4xdb6mGeAUgB19PLX-/edit?usp=sharing&ouid=115653807694612666399&rtpof=true&sd=true" target="_blank">
        <img src="/assets/img/tnail_2.png" alt="Movie Analysis Dashboard" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 03</span>
        <h3 class="project-title">Movie Performance and Profitability Analysis using Excel Dashboard</h3>
        <div class="project-tags">
          <span class="project-tag">Excel</span>
          <span class="project-tag">Data Visualization</span>
          <span class="project-tag">Dashboard Design</span>
        </div>
        <p class="project-description">
          Performed data cleaning, analysis, and visualization on a dataset of Hollywood movies to explore trends in budget, revenue, and ratings across years, genres, and production companies. Designed an interactive dashboard integrating pivot charts and slicers to uncover insights on profitability, audience preferences, and production performance.
        </p>
      </div>
      <a href="https://docs.google.com/spreadsheets/d/1PRsDHUQzEJgM6h4xdb6mGeAUgB19PLX-/edit?usp=sharing&ouid=115653807694612666399&rtpof=true&sd=true" target="_blank" class="project-link">
        View Dashboard
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/file/d/1DE64WGdTxbZrbLa_m5AyZTDSlHnVSZO-/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail2.png" alt="Restaurant Tips Analysis" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 04</span>
        <h3 class="project-title">Restaurant Tips Analysis</h3>
        <div class="project-tags">
          <span class="project-tag">SQL</span>
          <span class="project-tag">Python</span>
          <span class="project-tag">Regression Analysis</span>
        </div>
        <p class="project-description">
          Applied SQL, Python, and Gretl to evaluate drivers of tipping behavior in restaurants. Identified key customer and service factors shaping tipping decisions through statistical models. Provided actionable insights into consumer patterns for hospitality sector optimization.
        </p>
      </div>
      <a href="https://drive.google.com/file/d/1DE64WGdTxbZrbLa_m5AyZTDSlHnVSZO-/view?usp=sharing" target="_blank" class="project-link">
        View Report
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/file/d/1pMuQJvz8JNXRrVClzEXySzyNpG8HbE_R/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail3.png" alt="Vodafone Case Study" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 05</span>
        <h3 class="project-title">Business Case Study - Vodafone</h3>
        <div class="project-tags">
          <span class="project-tag">Strategy</span>
          <span class="project-tag">Market Analysis</span>
          <span class="project-tag">Case Study</span>
        </div>
        <p class="project-description">
          Analyzed the evolution of India's telecom industry with a focus on Vodafone's entry, merger with Idea, and strategic challenges. Evaluated market concentration, pricing disruption from Jio, and financial impacts such as AGR dues. Delivered strategic recommendations for competitive positioning.
        </p>
      </div>
      <a href="https://drive.google.com/file/d/1pMuQJvz8JNXRrVClzEXySzyNpG8HbE_R/view?usp=sharing" target="_blank" class="project-link">
        View Case Study
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/drive/folders/17DDzrFSeGdRjA_Oma8wAL4fD4M0Y1-iL?usp=drive_link" target="_blank">
        <img src="/assets/img/tnail4.png" alt="COMSOL Simulation" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 06</span>
        <h3 class="project-title">Simulation-based Study of Diffusion through Porous Membranes using COMSOL Multiphysics</h3>
        <div class="project-tags">
          <span class="project-tag">COMSOL</span>
          <span class="project-tag">Simulation</span>
          <span class="project-tag">Chemical Engineering</span>
        </div>
        <p class="project-description">
          Developed COMSOL multiphysics models to study diffusion and vapor transport in membranes. Analyzed coupled effects of geometry, porosity, flow, and temperature on transport phenomena. Discovered enhancement mechanisms that improve efficiency in porous membrane systems.
        </p>
      </div>
      <a href="https://drive.google.com/drive/folders/17DDzrFSeGdRjA_Oma8wAL4fD4M0Y1-iL?usp=drive_link" target="_blank" class="project-link">
        View Project
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/drive/folders/1ovd3u93y81AISCwJM5rUMYYT8mMA2RJS?usp=drive_link" target="_blank">
        <div style="width: 100%; height: 100%; background: linear-gradient(135deg, #667EEA 0%, #764BA2 100%); display: flex; align-items: center; justify-content: center; color: white; font-size: 3rem; font-weight: bold;">EG</div>
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 07</span>
        <h3 class="project-title">Simulation and Optimization of Ethylene Glycol Production from Ethylene Oxide</h3>
        <div class="project-tags">
          <span class="project-tag">Aspen Plus</span>
          <span class="project-tag">MATLAB</span>
          <span class="project-tag">Process Optimization</span>
        </div>
        <p class="project-description">
          Simulated continuous ethylene glycol production from ethylene oxide using Aspen Plus. Optimized process parameters to achieve 97.8% yield while minimizing by-products DEG/TEG. Integrated MATLAB parametric studies to validate efficiency with industrial-scale data.
        </p>
      </div>
      <a href="https://drive.google.com/drive/folders/1ovd3u93y81AISCwJM5rUMYYT8mMA2RJS?usp=drive_link" target="_blank" class="project-link">
        View Project
      </a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-image">
      <a href="https://drive.google.com/file/d/1igNGfvtLauIGPz-UvCzp3iqHAThWfWpB/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail6.png" alt="Heat Exchanger Design" />
      </a>
    </div>
    <div class="project-content">
      <div>
        <span class="project-number">Project 08</span>
        <h3 class="project-title">Efficiency and Effectiveness Calculation of Helical Fins in a Double Pipe Heat Exchanger</h3>
        <div class="project-tags">
          <span class="project-tag">Heat Transfer</span>
          <span class="project-tag">Design Optimization</span>
          <span class="project-tag">Engineering Calculations</span>
        </div>
        <p class="project-description">
          Designed and modeled a double pipe heat exchanger for process efficiency improvements. Performed calculations on heat transfer, pressure drops, and optimized design for performance. Validated theoretical designs with industrial standards for chemical process applications.
        </p>
      </div>
      <a href="https://drive.google.com/file/d/1igNGfvtLauIGPz-UvCzp3iqHAThWfWpB/view?usp=sharing" target="_blank" class="project-link">
        View Report
      </a>
    </div>
  </div>

</div>

<div style="text-align: center; margin-top: 3rem; padding: 2rem; background: linear-gradient(135deg, #667EEA 0%, #764BA2 100%); border-radius: 1rem; color: white;">
  <h2 style="color: white; margin-bottom: 1rem;">Interested in Collaboration?</h2>
  <p style="margin-bottom: 1.5rem; font-size: 1.125rem;">I'm always open to discussing new projects and opportunities.</p>
  <a href="mailto:dhruvisisodiya17@gmail.com" style="display: inline-block; background: white; color: #667EEA; padding: 0.875rem 2rem; border-radius: 0.5rem; font-weight: 600; text-decoration: none; transition: all 0.3s ease;">
    Get In Touch
  </a>
</div>
