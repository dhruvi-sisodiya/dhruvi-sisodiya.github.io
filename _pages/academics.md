---
layout: page
title: About Me
subtitle: Senior Undergraduate - IIT Gandhinagar
featured-on-home: false
description: Get to know me better. Learn about my story and what makes me unique.
---

<style>
.roadmap-container {
  position: relative;
  padding: 3rem 0;
  margin: 2rem 0;
}

.roadmap-path {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  position: relative;
  padding: 0 2rem 2rem 2rem;
  overflow-x: visible;
  gap: 1rem;
  flex-wrap: nowrap;
}

.roadmap-path::before {
  content: '';
  position: absolute;
  top: 30px;
  left: 12%;
  right: 12%;
  height: 3px;
  background: linear-gradient(90deg, #667EEA 0%, #764BA2 100%);
  z-index: 0;
}

.journey-milestone {
  flex: 1;
  min-width: 140px;
  text-align: center;
  position: relative;
  z-index: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.milestone-icon {
  width: 60px;
  height: 60px;
  margin: 0 auto 0.75rem;
  background: white;
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.5rem;
  box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
  transition: all 0.3s ease;
  border: 3px solid #667EEA;
}

.journey-milestone:hover .milestone-icon {
  transform: scale(1.15) rotate(5deg);
  box-shadow: 0 12px 30px rgba(102, 126, 234, 0.5);
}

.milestone-title {
  font-size: 0.85rem;
  font-weight: 700;
  color: #2D3748;
  margin-bottom: 0.4rem;
}

.milestone-subtitle {
  font-size: 0.75rem;
  color: #667EEA;
  font-weight: 600;
  margin-bottom: 0.2rem;
}

.milestone-detail {
  font-size: 0.7rem;
  color: #718096;
  line-height: 1.3;
}

@media (max-width: 768px) {
  .roadmap-path {
    flex-direction: column;
    gap: 3rem;
  }
  
  .roadmap-path::before {
    top: 0;
    bottom: 0;
    left: 50%;
    right: auto;
    width: 3px;
    height: auto;
    transform: translateX(-50%);
    background: linear-gradient(180deg, #667EEA 0%, #764BA2 100%);
  }
  
  .journey-milestone {
    min-width: 100%;
  }
}
</style>

<section class="intro-section" style="margin-bottom: 3rem;">
  <div style="text-align: center; max-width: 800px; margin: 0 auto 3rem;">
    <h2 style="font-size: 2.5rem; margin-bottom: 1rem;">Hi, I'm Dhruvi</h2>
    <p style="font-size: 1.125rem; line-height: 1.8; color: #4A5568;">
      A senior undergraduate at <strong>IIT Gandhinagar</strong> passionate about bridging the gap between engineering and business. I combine technical expertise with strategic thinking, analytics, and creative design to solve complex problems and drive innovation.
    </p>
  </div>
</section>

<section style="margin-bottom: 3rem;">
  <h2 style="font-size: 2rem; margin-bottom: 1.5rem; text-align: center;">My Journey</h2>
  
  <div class="roadmap-container">
    <div class="roadmap-path">
      <div class="journey-milestone">
        <div class="milestone-icon">🎓</div>
        <div class="milestone-title">Academic Foundation</div>
        <div class="milestone-subtitle">IIT Gandhinagar</div>
        <div class="milestone-detail">B.Tech Chemical Engineering</div>
      </div>
      
      <div class="journey-milestone">
        <div class="milestone-icon">📊</div>
        <div class="milestone-title">Analytics & Strategy</div>
        <div class="milestone-subtitle">Data-Driven Projects</div>
        <div class="milestone-detail">Python, SQL, Power BI</div>
      </div>
      
      <div class="journey-milestone">
        <div class="milestone-icon">🔬</div>
        <div class="milestone-title">Internships</div>
        <div class="milestone-subtitle">IOCL & DRDO-IITGN</div>
        <div class="milestone-detail">Process engineering & fuel cell research</div>
      </div>
      
      <div class="journey-milestone">
        <div class="milestone-icon">🎨</div>
        <div class="milestone-title">Creative Leadership</div>
        <div class="milestone-subtitle">TEDx '24 & Amalthea '23</div>
        <div class="milestone-detail">Design Team Lead & Coordinator</div>
      </div>
    </div>
  </div>
</section>

<section style="margin-bottom: 3rem;">
  <h2 style="font-size: 2rem; margin-bottom: 1.5rem; text-align: center;">Technical Skills</h2>
  
  <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem; max-width: 1000px; margin: 0 auto;">
    <div class="skill-card">
      <h3 style="color: #667EEA; margin-bottom: 0.75rem; font-size: 1rem;">💻 Programming & Analytics</h3>
      <ul style="list-style: none; padding: 0; font-size: 0.875rem;">
        <li style="padding: 0.25rem 0;">✓ Python, SQL, MATLAB</li>
        <li style="padding: 0.25rem 0;">✓ Excel, Power BI</li>
      </ul>
    </div>
    
    <div class="skill-card">
      <h3 style="color: #667EEA; margin-bottom: 0.75rem; font-size: 1rem;">🛠️ Engineering Tools</h3>
      <ul style="list-style: none; padding: 0; font-size: 0.875rem;">
        <li style="padding: 0.25rem 0;">✓ COMSOL, ANSYS</li>
        <li style="padding: 0.25rem 0;">✓ Aspen Plus, Inventor</li>
      </ul>
    </div>
    
    <div class="skill-card">
      <h3 style="color: #667EEA; margin-bottom: 0.75rem; font-size: 1rem;">🎨 Design & Communication</h3>
      <ul style="list-style: none; padding: 0; font-size: 0.875rem;">
        <li style="padding: 0.25rem 0;">✓ Adobe Illustrator, Canva</li>
        <li style="padding: 0.25rem 0;">✓ LaTeX, Brand Strategy</li>
      </ul>
    </div>
  </div>
</section>

<section style="margin-bottom: 3rem;">
  <h2 style="font-size: 2rem; margin-bottom: 1.5rem; text-align: center;">Areas of Interest</h2>
  
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 0.75rem; max-width: 900px; margin: 0 auto;">
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">Business Analytics</span>
    </div>
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">Strategy Consulting</span>
    </div>
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">Market Research</span>
    </div>
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">Product Development</span>
    </div>
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">User Research</span>
    </div>
    <div class="interest-card">
      <span style="color: #4A5568; font-weight: 600; font-size: 0.9375rem;">UI/UX Design</span>
    </div>
  </div>
</section>

<style>
.skill-card {
  background: white;
  padding: 1rem;
  border-radius: 0.5rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-left: 3px solid #667EEA;
  transition: all 0.3s ease;
  cursor: pointer;
}

.skill-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
  border-left: 3px solid #5A67D8;
}

.interest-card {
  background: white;
  padding: 0.75rem 1rem;
  border-radius: 0.5rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  border-left: 3px solid #667EEA;
  text-align: center;
  transition: all 0.3s ease;
  cursor: pointer;
}

.interest-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 6px 15px rgba(102, 126, 234, 0.3);
  border-left: 3px solid #5A67D8;
}
</style>
