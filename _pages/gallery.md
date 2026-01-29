---
layout: single
title: "Project Gallery"
permalink: /gallery/
author_profile: true
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
}

.gallery-item {
  background-color: #EEF3FA; /* Strata card */
  border-radius: 1rem;
  padding: 0.5rem;
  border: 1px solid #F2F2F2;
  box-shadow: 8px 8px 16px rgba(163,177,198,0.45), -8px -8px 16px rgba(255,255,255,0.90); /* Strata shadow-sm */
  transition: all 0.2s ease-in-out;
}

.gallery-item:hover {
  transform: translateY(-2px);
  box-shadow: 12px 12px 24px rgba(163,177,198,0.50), -12px -12px 24px rgba(255,255,255,0.92); /* Strata shadow-md */
}

.gallery-item img {
  width: 100%;
  height: auto;
  border-radius: 0.75rem;
  display: block;
}

.gallery-caption {
  padding: 0.75rem 0.5rem 0.5rem;
  font-family: "Outfit", sans-serif;
  font-size: 0.9rem;
  color: #22324A;
  text-align: center;
}
</style>

<div class="gallery-grid">
  <!-- Example Item 1 -->
  <div class="gallery-item">
    <img src="/assets/images/bio-photo.png" alt="Project Placeholder 1">
    <div class="gallery-caption">Project Alpha Visualization</div>
  </div>

  <!-- Example Item 2 -->
  <div class="gallery-item">
    <img src="/assets/images/bio-photo.png" alt="Project Placeholder 2">
    <div class="gallery-caption">Simulation Result</div>
  </div>

  <!-- Add more .gallery-item blocks here -->
</div>
