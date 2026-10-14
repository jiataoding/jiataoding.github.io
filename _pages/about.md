---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an **Assistant Professor in Embodied Intelligence** at **Beijing Zhongguancun Academy**, China. Before joining Beijing Zhongguancun Academy, I was a **Research Fellow** at the **University of Trento**, Italy, working with **Prof. Matteo Saveriano**. Previously, I was a **Postdoctoral Researcher** in the Department of Cognitive Robotics at **Delft University of Technology (TU Delft)**, the Netherlands, where I worked with **Prof. Cosimo Della Santina**, **Prof. Jens Kober**, and **Prof. Wei Pan**. Prior to that, I was an **Assistant Research Scientist** at the **Shenzhen Institute of Artificial Intelligence and Robotics for Society (AIRS)**, China, working with **Prof. Tin Lun Lam** and **Prof. Sethu Vijayakumar**.

I received my PhD in **Mechatronic Engineering** from **Wuhan University**, China. During my PhD, I was a visiting PhD fellow at the **Italian Institute of Technology (IIT)**, Italy, working with **Dr. Nikolaos Tsagarakis**.

I serve as an **Associate Editor of IEEE Robotics and Automation Letters (RA-L)** and regularly review for leading robotics and control journals and conferences, including **IEEE T-RO, T-MECH, T-IE, T-ASE, RA-L, RSS, ICRA, IROS, and L4DC**.

My research interests broadly lie in **robot learning, optimal control, and legged robotics**.

<style>
.research-video-grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 20px;
  margin: 24px 0;
}
.research-video-grid figure {
  margin: 0;
  min-width: 0;
}
.research-video-grid video {
  display: block;
  width: 100%;
  aspect-ratio: 16 / 9;
  object-fit: contain;
  background: #000;
  border-radius: 8px;
}
.research-video-grid figcaption {
  margin-top: 8px;
  font-size: 0.85em;
  font-weight: 600;
  line-height: 1.4;
  text-align: center;
}
@media (max-width: 600px) {
  .research-video-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="research-video-grid">
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Humanoid Push Recovery">
      <source src="{{ '/videos/humanoid_push_recovery.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Humanoid Push Recovery</figcaption>
  </figure>
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Safe Humanoid Locomotion">
      <source src="{{ '/videos/humanoid_safe_loco.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Safe Humanoid Locomotion</figcaption>
  </figure>
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Compliant Landing">
      <source src="{{ '/videos/quadruped_compliant_landing.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Compliant Landing</figcaption>
  </figure>
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Explosive Jumping">
      <source src="{{ '/videos/quadruped_explosive_jumping.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Explosive Jumping</figcaption>
  </figure>
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Frog-inspired Jumping">
      <source src="{{ '/videos/quadruped_froggy_jumping.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Frog-inspired Jumping</figcaption>
  </figure>
  <figure>
    <video controls muted loop playsinline preload="metadata" aria-label="Safety-critical Gear Meshing">
      <source src="{{ '/videos/gear_meshing_mosaic.mp4' | relative_url }}" type="video/mp4">
    </video>
    <figcaption>Safety-critical Gear Meshing</figcaption>
  </figure>
</div>
