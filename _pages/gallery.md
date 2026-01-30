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
  opacity: 1 !important;
  filter: none !important;
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

  <div class="gallery-item">
    <img src="/assets/images/grafana.png" alt="Grafana Weather Readings">
    <div class="gallery-caption">Snapshot of Grafana website I created to track meteorological data from instruments on UC San Diego's campus.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/shap.jpeg" alt="SHAP Chart">
    <div class="gallery-caption">SHAP importance chart I created to assess urban form feature importance for predicting pedestrian activity.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/clipper-prototype.png" alt="Clipper Prototype">
    <div class="gallery-caption">Assembled prototype of endoscopic multiload clip applier I collaborated in designing and manufacturing.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/northpark.png" alt="North Park Maps">
    <div class="gallery-caption">GIS graphic I created showing amenity access for each household in San Diego's North Park neighborhood.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/amp-phase.png" alt="Amplitude Phase Graph">
    <div class="gallery-caption">Graph I created showing amplitude and phase offsets of particles in an oscillatory fluid based on relative density and frequency.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/solar-equipment.png" alt="Solar Equipment">
    <div class="gallery-caption">Physical installation of meteorological instruments I maintained at UC San Diego.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/ach-sim.gif" alt="ACH Simulation">
    <div class="gallery-caption">Simulation I collaborated to create for an undergraduate fluids course of air circulation in a classroom.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/sub-dive-min.gif" alt="Submarine Dive">
    <div class="gallery-caption">Demonstration of open-ocean diving capability for underwater research vehicle I manufactured parts for.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/autobreaking-min.gif" alt="Auto-Breaking Mechanism">
    <div class="gallery-caption">Demonstration of breaking behavior I programmed for a model wind turbine rotor.</div>
  </div>  

  <div class="gallery-item">
    <img src="/assets/images/kinematic-experiment.jpg" alt="Kinematic Experiment">
    <div class="gallery-caption">Miniature cannon fabricated and assembled for an  undergraduate machining class.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/best-boy.jpg" alt="Best Boy">
    <div class="gallery-caption">Full image version of website favicon.</div>
  </div>

  <div class="gallery-item">
    <img src="/assets/images/hose.jpeg" alt="Hose Play">
    <div class="gallery-caption">Little dude really loves playing with the hose!</div>
  </div>

</div>
