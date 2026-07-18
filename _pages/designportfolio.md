---
layout: page
title: Design Portfolio
subtitle: A showcase of my Graphic Design work 
featured-on-home: true
description: Explore the variety of Posts, Printing media, Merchandise etc that I had created for my College Summits.
thumbnail-img: "/assets/img/design12.jpeg"
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

.design-carousel-card {
  min-width: 350px;
  max-width: 350px;
  background: white;
  border-radius: 20px;
  overflow: hidden;
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  flex-shrink: 0;
}

.design-carousel-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 20px 40px rgba(30, 58, 138, 0.2),
              0 0 20px rgba(37, 99, 235, 0.4),
              0 0 35px rgba(29, 78, 216, 0.3);
}

.tedx-card:hover {
  box-shadow: 0 20px 40px rgba(185, 28, 28, 0.2),
              0 0 20px rgba(220, 38, 38, 0.4),
              0 0 35px rgba(239, 68, 68, 0.3);
}

.design-image {
  width: 100%;
  height: auto;
  aspect-ratio: 1/1;
  object-fit: cover;
  display: block;
}

@media (max-width: 1200px) {
  .design-carousel-card {
    min-width: 320px;
    max-width: 320px;
  }
}

@media (max-width: 992px) {
  .design-carousel-card {
    min-width: 300px;
    max-width: 300px;
  }
  
  .carousel-wrapper {
    gap: 25px;
  }
}

@media (max-width: 768px) {
  .design-carousel-card {
    min-width: calc(100vw - 80px);
    max-width: calc(100vw - 80px);
  }
  
  .carousel-wrapper {
    gap: 20px;
    padding: 20px 40px 40px 40px;
  }
}

@media (max-width: 480px) {
  .design-carousel-card {
    min-width: calc(100vw - 60px);
    max-width: calc(100vw - 60px);
  }
  
  .carousel-wrapper {
    gap: 15px;
    padding: 20px 30px 40px 30px;
  }
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

.tedx-drag {
  color: #DC2626;
}

.tedx-drag::before,
.tedx-drag::after {
  background: linear-gradient(90deg, transparent, #DC2626, transparent) !important;
}

@keyframes slideHint {
  0%, 100% { transform: translateX(0); opacity: 1; }
  50% { transform: translateX(10px); opacity: 0.7; }
}

.section-intro {
  max-width: 1500px;
  margin: 0 auto 40px;
  padding: 0;
}
</style>

<div class="section-intro">
  <p>I have a strong interest in graphic design and visual presentation, which I've developed through key leadership roles at IIT Gandhinagar.</p>
</div>

<h1 class="roboto-heading">TEDxIITGandhinagar '24</h1>

<p style="max-width: 1500px; margin: 0 auto 30px; padding: 0;">As Design Team Lead, I guided a team of 10 members. I worked on creating the event's identity across merchandise, social media campaigns, and stage design.</p>

<h2 class="roboto-heading" style="font-weight:normal;">Social Media Posts</h2>

<div class="carousel-container">
  <div class="carousel-wrapper" id="tedxSocialCarousel">
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design1.png" alt="Design 1" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design2.png" alt="Design 2" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design3.png" alt="Design 3" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design4.png" alt="Design 4" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design5.png" alt="Design 5" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design7.png" alt="Design 7" class="design-image">
    </div>
  </div>
  <div class="drag-hint tedx-drag">
    <span>→ Drag to explore more</span>
  </div>
</div>

<h2 class="roboto-heading" style="font-weight:normal;">TEDx Merchandise</h2> 

<div class="carousel-container">
  <div class="carousel-wrapper" id="tedxMerchCarousel">
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/design6.png" alt="Brochure" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/merch1.png" alt="Merchandise 1" class="design-image">
    </div>
    <div class="design-carousel-card tedx-card">
      <img src="/assets/img/merch2.png" alt="Merchandise 2" class="design-image">
    </div>
  </div>
  <div class="drag-hint tedx-drag">
    <span>→ Drag to explore more</span>
  </div>
</div>

---

<h1 class="roboto-heading">Amalthea '23 (Annual Tech Summit of IIT Gandhinagar)</h1>

<p style="max-width: 1500px; margin: 0 auto 30px; padding: 0;">As Design Team Coordinator, I led a 25-member team. I built a cohesive brand presence through social media outreach and large-scale design work across campus and city installations.</p>

<h2 class="roboto-heading" style="font-weight:normal;">Social Media Posts</h2>

<div class="carousel-container">
  <div class="carousel-wrapper" id="amaltheaSocialCarousel">
    <div class="design-carousel-card">
      <img src="/assets/img/TT5_P1.png" alt="TT5 P1" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT5_P2.png" alt="TT5 P2" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT5_P3.png" alt="TT5 P3" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT5_P4.png" alt="TT5 P4" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT7_01.png" alt="TT7 P1" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT7_02.png" alt="TT7 P2" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT7_03.png" alt="TT7 P3" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/TT7_04.png" alt="TT7 P4" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/design11.png" alt="Design 11" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/design9.png" alt="Design 9" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/design10.png" alt="Design 10" class="design-image">
    </div>
  </div>
  <div class="drag-hint">
    <span>→ Drag to explore more</span>
  </div>
</div>

<h2 class="roboto-heading" style="font-weight:normal;">Merchandise and Printing Media</h2>

<div class="carousel-container">
  <div class="carousel-wrapper" id="amaltheaMerchCarousel">
    <div class="design-carousel-card">
      <img src="/assets/img/design12.jpeg" alt="Design 12" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/design13.png" alt="Design 13" class="design-image">
    </div>
    <div class="design-carousel-card">
      <img src="/assets/img/merch3.png" alt="Merch 3" class="design-image">
    </div>
  </div>
  <div class="drag-hint">
    <span>→ Drag to explore more</span>
  </div>
</div>

<script>
// Draggable carousel functionality for all carousels
const carousels = document.querySelectorAll('.carousel-wrapper');

carousels.forEach(carousel => {
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
});
</script>
