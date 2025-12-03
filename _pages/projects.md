---
layout: page
title: My Projects
subtitle: A showcase of intensive Academic Projects
featured-on-home: true
description: Explore my portfolio of projects, from web development to creative endeavors. See what I've been working on lately.
thumbnail-img: "/assets/img/tnail_1.png"
---

<style>
.carousel-container {
  position: relative;
  width: 100vw;
  max-width: 100vw;
  margin-left: calc(-50vw + 50%);
  margin-right: calc(-50vw + 50%);
  padding: 40px 0;
  overflow: hidden;
}

.carousel-wrapper {
  display: flex;
  gap: 30px;
  overflow-x: auto;
  scroll-behavior: smooth;
  padding: 20px 80px 40px 80px;
  cursor: grab;
  user-select: none;
  -webkit-overflow-scrolling: touch;
  scrollbar-width: none;
}

.carousel-wrapper::-webkit-scrollbar {
  display: none;
}

.carousel-wrapper:active {
  cursor: grabbing;
}

.project-carousel-card {
  min-width: 450px;
  max-width: 450px;
  background: white;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  flex-shrink: 0;
}

.project-carousel-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(30, 58, 138, 0.2),
              0 0 20px rgba(37, 99, 235, 0.4),
              0 0 35px rgba(29, 78, 216, 0.3);
}

@media (max-width: 1200px) {
  .project-carousel-card {
    min-width: 400px;
    max-width: 400px;
  }
}

@media (max-width: 992px) {
  .project-carousel-card {
    min-width: 380px;
    max-width: 380px;
  }
  
  .carousel-wrapper {
    gap: 25px;
  }
}

@media (max-width: 768px) {
  .project-carousel-card {
    min-width: calc(100vw - 80px);
    max-width: calc(100vw - 80px);
  }
  
  .carousel-wrapper {
    gap: 20px;
    padding: 20px 40px 40px 40px;
  }
}

@media (max-width: 480px) {
  .project-carousel-card {
    min-width: calc(100vw - 60px);
    max-width: calc(100vw - 60px);
  }
  
  .carousel-wrapper {
    gap: 15px;
    padding: 20px 30px 40px 30px;
  }
  
  .project-content {
    padding: 20px;
  }
}

.project-carousel-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(102, 126, 234, 0.2);
}

.project-image {
  width: 100%;
  height: auto;
  aspect-ratio: 16/9;
  object-fit: contain;
  display: block;
  background: #F7FAFC;
}

.project-content {
  padding: 25px;
}

.project-title {
  font-size: 1.4rem;
  font-weight: 700;
  color: #2D3748;
  margin-bottom: 12px;
  line-height: 1.3;
}

.project-description {
  font-size: 0.95rem;
  color: #4A5568;
  line-height: 1.6;
  margin-bottom: 20px;
  display: -webkit-box;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
  overflow: hidden;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-bottom: 20px;
}

.project-tag {
  padding: 6px 14px;
  background: #EDF2F7;
  color: #667EEA;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 600;
}

.project-link {
  display: inline-block;
  padding: 10px 24px;
  background: white;
  color: #667EEA;
  text-decoration: none;
  border-radius: 25px;
  font-weight: 600;
  font-size: 0.9rem;
  border: 2px solid #667EEA;
  box-shadow: 0 0 10px rgba(102, 126, 234, 0.3);
  transition: all 0.3s ease;
}

.project-link:hover {
  transform: translateY(-2px);
  box-shadow: 0 0 20px rgba(102, 126, 234, 0.6), 0 0 30px rgba(102, 126, 234, 0.4);
  color: #667EEA;
  text-decoration: none;
  border-color: #764BA2;
}

.drag-hint {
  text-align: center;
  margin-top: 30px;
  color: #667EEA;
  font-size: 0.9rem;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 15px;
  letter-spacing: 0.5px;
}

.drag-hint::before,
.drag-hint::after {
  content: '';
  display: inline-block;
  width: 60px;
  height: 2px;
  background: linear-gradient(90deg, transparent, #667EEA, transparent);
}

.drag-hint span {
  position: relative;
  animation: slideHint 2s ease-in-out infinite;
}

@keyframes slideHint {
  0%, 100% { transform: translateX(0); opacity: 1; }
  50% { transform: translateX(10px); opacity: 0.7; }
}
</style>

<div class="carousel-container">
  <div class="carousel-wrapper" id="projectCarousel">
    
    <div class="project-carousel-card">
      <a href="https://drive.google.com/drive/folders/1JX4vxVmLHawc6d335NAPNy5jrZ5mIUHb?usp=sharing" target="_blank">
        <img src="/assets/img/tnail_1.png" alt="Sales Analytics Dashboard" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Sales Analytics Dashboard</h3>
        <div class="project-tags">
          <span class="project-tag">Power BI</span>
          <span class="project-tag">Analytics</span>
        </div>
        <p class="project-description">
          Interactive Power BI dashboard analyzing global electronics retail sales, integrating six datasets to visualize revenue, profit, and regional trends for data-driven decisions.
        </p>
        <a href="https://drive.google.com/drive/folders/1JX4vxVmLHawc6d335NAPNy5jrZ5mIUHb?usp=sharing" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://github.com/dhruvi-sisodiya/business_intelligence-AI_chatbot_disclosure" target="_blank">
        <img src="/assets/img/tnail1.png" alt="AI Chatbot Analysis" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">AI Chatbot Disclosure Analysis</h3>
        <div class="project-tags">
          <span class="project-tag">SQL</span>
          <span class="project-tag">Python</span>
        </div>
        <p class="project-description">
          Experimental study using SQL, Python, and Gretl to analyze AI chatbot disclosure and customer behavior, revealing financial attributes' influence on purchase decisions.
        </p>
        <a href="https://github.com/dhruvi-sisodiya/business_intelligence-AI_chatbot_disclosure" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/file/d/14aaRboA4eHZRqhszYNiB4k90aCoICSUW/view?usp=sharing" target="_blank">
        <img src="/assets/img/AirBNB_Thumbnail.png" alt="Airbnb NYC Analysis" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Analysis of Airbnb New York Dataset</h3>
        <div class="project-tags">
          <span class="project-tag">Marketing Analytics</span>
          <span class="project-tag">Data Analysis</span>
        </div>
        <p class="project-description">
          Comprehensive analysis of Airbnb NYC dataset examining listing patterns, pricing trends, room types distribution, and booking metrics to uncover market insights.
        </p>
        <a href="https://drive.google.com/file/d/14aaRboA4eHZRqhszYNiB4k90aCoICSUW/view?usp=sharing" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://docs.google.com/spreadsheets/d/1PRsDHUQzEJgM6h4xdb6mGeAUgB19PLX-/edit?usp=sharing&ouid=115653807694612666399&rtpof=true&sd=true" target="_blank">
        <img src="/assets/img/tnail_2.png" alt="Movie Analytics" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Movie Performance Analysis</h3>
        <div class="project-tags">
          <span class="project-tag">Excel</span>
          <span class="project-tag">Dashboard</span>
        </div>
        <p class="project-description">
          Data cleaning and visualization of Hollywood movies exploring budget, revenue, and ratings trends. Interactive dashboard with pivot charts for profitability insights.
        </p>
        <a href="https://docs.google.com/spreadsheets/d/1PRsDHUQzEJgM6h4xdb6mGeAUgB19PLX-/edit?usp=sharing&ouid=115653807694612666399&rtpof=true&sd=true" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/file/d/1DE64WGdTxbZrbLa_m5AyZTDSlHnVSZO-/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail2.png" alt="Restaurant Tips" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Restaurant Tips Analysis</h3>
        <div class="project-tags">
          <span class="project-tag">SQL</span>
          <span class="project-tag">Statistics</span>
        </div>
        <p class="project-description">
          Applied SQL, Python, and Gretl to evaluate tipping behavior drivers, identifying key customer and service factors through statistical models for hospitality optimization.
        </p>
        <a href="https://drive.google.com/file/d/1DE64WGdTxbZrbLa_m5AyZTDSlHnVSZO-/view?usp=sharing" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/file/d/1pMuQJvz8JNXRrVClzEXySzyNpG8HbE_R/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail3.png" alt="Vodafone Case Study" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Business Case Study - Vodafone</h3>
        <div class="project-tags">
          <span class="project-tag">Strategy</span>
          <span class="project-tag">Analysis</span>
        </div>
        <p class="project-description">
          Analyzed India's telecom industry evolution, focusing on Vodafone's entry, Idea merger, and strategic challenges including market concentration and AGR dues impact.
        </p>
        <a href="https://drive.google.com/file/d/1pMuQJvz8JNXRrVClzEXySzyNpG8HbE_R/view?usp=sharing" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/drive/folders/17DDzrFSeGdRjA_Oma8wAL4fD4M0Y1-iL?usp=drive_link" target="_blank">
        <img src="/assets/img/tnail4.png" alt="COMSOL Simulation" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Membrane Diffusion Study</h3>
        <div class="project-tags">
          <span class="project-tag">COMSOL</span>
          <span class="project-tag">Simulation</span>
        </div>
        <p class="project-description">
          COMSOL multiphysics models studying diffusion and vapor transport in membranes, analyzing coupled effects of geometry, porosity, and temperature on efficiency.
        </p>
        <a href="https://drive.google.com/drive/folders/17DDzrFSeGdRjA_Oma8wAL4fD4M0Y1-iL?usp=drive_link" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/drive/folders/1ovd3u93y81AISCwJM5rUMYYT8mMA2RJS?usp=drive_link" target="_blank">
        <img src="/assets/img/tnail1.png" alt="Ethylene Glycol" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Ethylene Glycol Production</h3>
        <div class="project-tags">
          <span class="project-tag">Aspen Plus</span>
          <span class="project-tag">MATLAB</span>
        </div>
        <p class="project-description">
          Simulated continuous ethylene glycol production using Aspen Plus, optimizing parameters to achieve 97.8% yield with MATLAB parametric validation.
        </p>
        <a href="https://drive.google.com/drive/folders/1ovd3u93y81AISCwJM5rUMYYT8mMA2RJS?usp=drive_link" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

    <div class="project-carousel-card">
      <a href="https://drive.google.com/file/d/1igNGfvtLauIGPz-UvCzp3iqHAThWfWpB/view?usp=sharing" target="_blank">
        <img src="/assets/img/tnail6.png" alt="Heat Exchanger" class="project-image">
      </a>
      <div class="project-content">
        <h3 class="project-title">Helical Fins Heat Exchanger</h3>
        <div class="project-tags">
          <span class="project-tag">Design</span>
          <span class="project-tag">Analysis</span>
        </div>
        <p class="project-description">
          Designed and modeled a double pipe heat exchanger, performing calculations on heat transfer and pressure drops, validated with industrial standards.
        </p>
        <a href="https://drive.google.com/file/d/1igNGfvtLauIGPz-UvCzp3iqHAThWfWpB/view?usp=sharing" target="_blank" class="project-link">View Project</a>
      </div>
    </div>

  </div>
  
  <div class="drag-hint">
    <span>→ Drag to explore more projects</span>
  </div>
</div>

<script>
// Draggable carousel functionality
const carousel = document.getElementById('projectCarousel');
let isDown = false;
let startX;
let scrollLeft;

carousel.addEventListener('mousedown', (e) => {
  isDown = true;
  carousel.style.cursor = 'grabbing';
  startX = e.pageX - carousel.offsetLeft;
  scrollLeft = carousel.scrollLeft;
});

carousel.addEventListener('mouseleave', () => {
  isDown = false;
  carousel.style.cursor = 'grab';
});

carousel.addEventListener('mouseup', () => {
  isDown = false;
  carousel.style.cursor = 'grab';
});

carousel.addEventListener('mousemove', (e) => {
  if (!isDown) return;
  e.preventDefault();
  const x = e.pageX - carousel.offsetLeft;
  const walk = (x - startX) * 2;
  carousel.scrollLeft = scrollLeft - walk;
});

// Touch support for mobile
carousel.addEventListener('touchstart', (e) => {
  startX = e.touches[0].pageX - carousel.offsetLeft;
  scrollLeft = carousel.scrollLeft;
});

carousel.addEventListener('touchmove', (e) => {
  const x = e.touches[0].pageX - carousel.offsetLeft;
  const walk = (x - startX) * 2;
  carousel.scrollLeft = scrollLeft - walk;
});
</script>
