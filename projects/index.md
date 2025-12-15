---
layout: default
title: Projects
permalink: /projects/
---

<style>
/* ===== Projects layout ===== */
.projects-section {
  margin-top: 0;
}

.category {
  margin-bottom: 4rem;
}

.category h2 {
  font-size: 1.6rem;
  margin-bottom: 0.5rem;
}

.category p {
  color: #666;
  margin-bottom: 1.5rem;
}

/* Grid */
.project-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5rem;
  width: 100%;
}

@media (min-width: 860px) {
  .project-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

/* Card */
.project-card {
  border: 1px solid #e5e5e5;
  border-radius: 12px;
  overflow: hidden;
  background: #fff;
  transition: transform 0.25s ease, box-shadow 0.25s ease, opacity 0.25s ease;
  width: 100%;
  display: flex;
  flex-direction: column;
}

.project-card img {
  width: 100%;
  height: 160px;
  object-fit: cover; /* keeps image clean & same size */
  display: block;
}

.project-card-content {
  padding: 1rem 1.25rem;
  flex-grow: 1;
  display: flex;
  flex-direction: column;
}

.project-card h3 {
  margin: 0 0 0.4rem;
  font-size: 1.05rem;
}

.project-card p {
  margin: 0;
  color: #666;
  font-size: 0.95rem;
  line-height: 1.4;
}

/* Hover effect */
.project-card:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 28px rgba(0,0,0,0.08);
}

.project-grid:hover .project-card {
  opacity: 0.45;
}

.project-grid:hover .project-card:hover {
  opacity: 1;
}
</style>

<section class="projects-section">
  <h1>Projects</h1>


  <!-- ================= API & PLATFORMS ================= -->
  <div class="category">
    <h2>API & Platform Systems</h2>
    <p>Designing self-serve workflows, integrations, and internal platforms that scale without adding headcount.</p>

    <div class="project-grid">
      <a href="/projects/crm/onlinequotation/" class="project-card">
        <img src="/assets/img/onlinequotation.png" alt="Online Quotation System">
        <div class="project-card-content">
          <h3>Online Quotation System</h3>
          <p>Self-serve CRM workflow that reduced quote turnaround from days to under an hour.</p>
        </div>
      </a>

      <div class="project-card">
        <img src="/assets/img/payment.png" alt="Payment Automation">
        <div class="project-card-content">
          <h3>Payment Automation</h3>
          <p>Automated vendor payment flow to reduce manual reconciliation and delays.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- ================= AI / ML ================= -->
  <div class="category">
    <h2>AI / ML Products</h2>
    <p>Lightweight, human-centered AI systems focused on real-world adoption.</p>

    <div class="project-grid">
      <div class="project-card">
        <img src="/assets/img/30-sec-ai-mood-checkin.png" alt="30-second mood check-in">
        <div class="project-card-content">
          <h3>30-Second Mood Check-In</h3>
          <p>AI-powered emotional check-in designed for daily use with minimal friction.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- ================= PROCESS OPTIMIZATION ================= -->
  <div class="category">
    <h2>Process Optimization & Scale</h2>
    <p>Turning messy operations into repeatable systems that teams actually use.</p>

    <div class="project-grid">
      <div class="project-card">
        <img src="/assets/img/placeholder.png" alt="Operational SOPs">
        <div class="project-card-content">
          <h3>Operational SOP Framework</h3>
          <p>Standardized workflows and training to support rapid organizational growth.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- ================= BLOOMPAL ================= -->
  <div class="category">
    <h2>BloomPal — AI for Wellness</h2>
    <p>Founder-led case studies from building and scaling an AI companion for mental wellness.</p>

    <div class="project-grid">
      <div class="project-card">
        <img src="/assets/img/placeholder.png" alt="BloomPal MVP">
        <div class="project-card-content">
          <h3>BloomPal MVP</h3>
          <p>Calendar-synced micro-rituals that turn tiny gaps into science-backed moments of care.</p>
        </div>
      </div>

      <div class="project-card">
        <img src="/assets/img/placeholder.png" alt="Active Feedback System">
        <div class="project-card-content">
          <h3>In-App Feedback System</h3>
          <p>Real-time feedback loops to improve engagement and personalization.</p>
        </div>
      </div>
    </div>
  </div>
</section>
