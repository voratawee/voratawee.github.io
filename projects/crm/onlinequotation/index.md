---
layout: case-study
title: Online Quotation System
---

<style>
.container {
  max-width: 900px;
  margin: 0 auto;
  padding: 3rem 2rem;
}

.tag {
  display: inline-block;
  background: rgba(0,0,0,0.06);
  padding: 0.4rem 1rem;
  border-radius: 20px;
  font-size: 0.85rem;
  margin-bottom: 1rem;
}

.subtitle {
  color: #666;
  font-size: 1.1rem;
  margin-bottom: 3rem;
}

.hero {
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 6px 24px rgba(0,0,0,0.12);
  margin-bottom: 4rem;
}

.hero img {
  width: 100%;
  display: block;
}

.project-section {
  margin-bottom: 4rem;
}

.label {
  text-transform: uppercase;
  letter-spacing: 1.5px;
  font-size: 0.75rem;
  color: #999;
  margin-bottom: 1rem;
}

.skills-list li {
  margin-bottom: 0.6rem;
}

.divider {
  height: 1px;
  background: #e5e5e5;
  margin: 4rem 0;
}

.image-placeholder {
  margin: 2rem 0;
  padding: 1.5rem;
  border: 1px dashed #ccc;
  background: #fafafa;
  color: #666;
  font-style: italic;
  text-align: center;
}

.impact-table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 2rem;
}

.impact-table th,
.impact-table td {
  text-align: left;
  padding: 1rem;
  border-bottom: 1px solid #eaeaea;
}

.impact-table th {
  color: #666;
  font-weight: 600;
}

.highlight {
  font-weight: 700;
}
</style>

<div class="container">

<span class="tag">CRM & Workflow Automation</span>

<h1>From 14 Days to 1 Hour: Building a Quotation System That Scales</h1>

<p class="subtitle">
Reduced quote turnaround by <strong>96%</strong>, unlocked <strong>$5M in revenue</strong>,
and scaled quoting to <strong>200+ installers</strong> without adding headcount.
</p>

<div class="hero">
  <img src="/assets/img/onlinequotation.png" alt="Online Quotation System">
</div>

<section class="project-section">
  <div class="label">What this project demonstrates</div>
  <ul class="skills-list">
    <li>Strategic build-vs-buy decision making under revenue pressure</li>
    <li>Designing systems for non-technical users at scale</li>
    <li>Low-code + backend reuse to ship 10× faster</li>
    <li>Operational automation as a growth lever</li>
    <li>Change management across 200+ service providers</li>
  </ul>
</section>

<div class="divider"></div>

<p><strong>Technologies:</strong> JotForm (Low-code/Frontend Abstraction), Progressive Web App (PWA), Internal Pricing Engine (API), Conditional Logic Engine, Automated Email Workflows, Internal Database Integration.</p>

<section class="project-section">
  <div class="label">I. Challenge: Latency and Friction</div>

  <p>
  At a rapidly growing Southeast Asian Home & Living E-commerce Platform, the traditional manual,
  paper-based customer quotation process for installation services created severe operational friction.
  </p>

  <ul>
    <li><strong>Problem:</strong> Quote delivery time averaged <strong>7–14 days</strong>, double the 7-day industry standard.</li>
    <li><strong>Impact:</strong> This latency caused <strong>50% of all customer complaints</strong> and revenue loss from abandoned leads.</li>
    <li><strong>Constraint:</strong> Over <strong>90% of our 200+ service providers</strong> lacked digital tools, forcing a system solution that was simple for the user but complex in its automation.</li>
  </ul>

  <div class="image-placeholder">
    [Place Image 1 Here: The "Before" State – Chaos and Bottlenecks]
  </div>
</section>

<section class="project-section">
  <div class="label">II. Strategic Pivot: Build vs. Integrate</div>

  <p>
  The internal development team scoped a custom tool at <strong>6+ months</strong>.
  Recognizing this delay as a strategic business failure, I led a critical pivot:
  <strong>Integrate existing systems to build a Minimum Viable Platform (MVP) in weeks.</strong>
  </p>

  <table class="impact-table">
    <tr>
      <th>Option</th>
      <th>Timeline</th>
      <th>Outcome</th>
      <th>Strategic Insight</th>
    </tr>
    <tr>
      <td>Custom-Build</td>
      <td>6+ months</td>
      <td>Perfect Architecture</td>
      <td>Rejected. Prioritized speed-to-value over ideal architecture.</td>
    </tr>
    <tr>
      <td><strong>Adapt & Integrate</strong></td>
      <td><strong>3 weeks</strong></td>
      <td>Operational MVP</td>
      <td>Decoupled the UI from the logic; focused resources on API integration.</td>
    </tr>
  </table>
</section>

<section class="project-section">
  <div class="label">III. Architecture: Workflow Automation via API Backbone</div>

  <p>
  I architected a solution to automate the entire workflow by leveraging our core
  <strong>Internal Pricing Engine API</strong>.
  </p>

  <div class="image-placeholder">
    [Place Image 2 Here: Architectural Diagram – The Automated Flow]
  </div>

  <ol>
    <li><strong>Frontend Abstraction (PWA):</strong> Low-code Progressive Web App enabling 90% adoption.</li>
    <li><strong>Smart Rules Engine:</strong> Dynamic conditional logic invoking real-time pricing via API.</li>
    <li><strong>API & Workflow Automation:</strong> Real-time pricing, persistence, and automated customer email delivery.</li>
  </ol>

  <p>
  <strong>The flow:</strong> Installer → PWA → Conditional Logic → Internal Pricing API → Automated Quote Email.
  </p>
</section>

<section class="project-section">
  <div class="label">IV. Quantified Impact and Platform Scaling</div>

  <table class="impact-table">
    <tr>
      <th>Metric</th>
      <th>Before</th>
      <th>After</th>
      <th>Improvement</th>
    </tr>
    <tr>
      <td>Quote Delivery Time</td>
      <td>14 Days</td>
      <td class="highlight">&lt;1 Hour</td>
      <td class="highlight">96% Reduction</td>
    </tr>
    <tr>
      <td>Customer Satisfaction</td>
      <td>Low (High Complaints)</td>
      <td class="highlight">+90%</td>
      <td>Post-service survey increase</td>
    </tr>
    <tr>
      <td>Complaints (Wait Time)</td>
      <td>50% of Total</td>
      <td class="highlight">Zero</td>
      <td>Primary pain point resolved</td>
    </tr>
    <tr>
      <td>Revenue Enablement</td>
      <td>Hindered Growth</td>
      <td class="highlight">$5M Generated</td>
      <td>Without operational cost increase</td>
    </tr>
  </table>

  <div class="image-placeholder">
    [Place Image 3 Here: The "After" State – Harmonious Flow & Growth]
  </div>
</section>

<section class="project-section">
  <div class="label">V. Strategic Learnings: Platform Blueprint</div>

  <ol>
    <li><strong>Technical Debt is Strategic:</strong> Low-code UI protected core API logic while shipping revenue fast.</li>
    <li><strong>API Integration is Core:</strong> Created a scalable foundation for future service automation.</li>
    <li><strong>Automation Requires Adoption:</strong> Training and trust were as critical as the system itself.</li>
  </ol>
</section>

<p><a href="/projects/">← Back to all projects</a></p>

</div>
