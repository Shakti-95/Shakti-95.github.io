---
layout: home
hero_image: "/assets/images/hero-bg.jpg"   # optional full-width banner
hero_title: "Shakti Prasad Padhy, Ph.D."
hero_subtitle: "AI-Driven Materials Discovery & Consulting"
hero_cta:
  - text: "View CV"
    url: "/cv/"
  - text: "Get in Touch"
    url: "/contact/"
---

Welcome! I’m a materials-informatics researcher and consultant, specializing in:

- **Inverse Alloy Design** via Bayesian optimization  
- **High-Throughput Experimentation** pipelines  
- **Explainable ML** for finite-element & spectroscopy data  

---

## 🚀 Featured Projects

<div class="row">
  <div class="col-4">
  **Inverse Design of Fe-Co-Ni Alloys**  
  Bayesian optimization → Experimental validation.  
  <a href="/projects/#fe-conical-alloys">Learn more →</a>
  </div>

  <div class="col-4">
  **Explainable FEA Deflection**  
  SHAP & LIME insights on boundary-condition sensitivity.  
  <a href="/projects/#fea-deflection">Read post →</a>
  </div>

  <div class="col-4">
  **Automated Workflow**  
  Batch-wise multi-objective BO for spark-plasma sintering.  
  <a href="/projects/#sps-optimization">Explore →</a>
  </div>
</div>

---

## 💼 Services

- **Alloy-Design Consulting:** ML-driven composition & process optimization  
- **High-Throughput Setup:** Design of experiments, automation & data pipelines  
- **Workshops & Training:** Intro to Bayesian optimization, SHAP, Jupyter  

---

## 📰 From the Blog

{% for post in site.posts limit:3 %}
- **[{{ post.title }}]({{ post.url }})** — {{ post.excerpt | strip_html | truncate: 80 }}
{% endfor %}

[View All Posts →](/blog/)

---

Want to collaborate or learn more?  
👉 **[Contact me](/contact/)**  
