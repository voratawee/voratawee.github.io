---
layout: case-study
title: Online Quotation System
---

<style> 

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

  /* Architecture / system diagrams */
.diagram {
  max-width: 820px;
  margin: 3rem auto;
  padding: 1.5rem;
  background: #fafafa;
  border-radius: 16px;
  box-shadow: 0 12px 36px rgba(0,0,0,0.12);
}

.diagram img {
  width: 100%;
  display: block;
  border-radius: 10px;
}

/* Supporting visuals (before / after) */
.supporting-image {
  max-width: 640px;
  margin: 3rem auto;
}

.supporting-image img {
  width: 100%;
  display: block;
  border-radius: 10px;
}

</style>

<div>

<span class="tag">API & Platform Systems</span>

<h1>From 14 Days to 1 Hour: Building a Quotation System That Scales</h1>

<p class="subtitle">
Reduced quote turnaround by <strong>96%</strong>, unlocked <strong>$5M in revenue</strong>,
and scaled quoting to <strong>200+ installers</strong> without adding headcount.
</p>

<div class="hero">
  <img src="/assets/img/onlinequotation.png" alt="Online Quotation System">
</div>

  <h3>What this project demonstrates</h3>
  <ul class="skills-list">
    <li>Strategic build-vs-buy decision making under revenue pressure</li>
    <li>Designing systems for non-technical users at scale</li>
    <li>Low-code + backend reuse to ship 10× faster</li>
    <li>Operational automation as a growth lever</li>
    <li>Change management across 200+ service providers</li>
  </ul>

<p><strong>Technologies:</strong> JotForm (Low-code/Frontend Abstraction), Progressive Web App (PWA), Internal Pricing Engine (API), Conditional Logic Engine, Automated Email Workflows, Internal Database Integration.</p>

<div class="divider"></div>

<h2>I. Challenge: Latency and Friction</h2>

  <p>
  At a rapidly growing Southeast Asian Home & Living E-commerce Platform, the traditional manual, paper-based customer quotation process for installation services created severe operational friction.
  </p>

  <ul>
    <li><strong>Problem:</strong> Quote delivery time averaged 7–14 days, double the 7-day industry standard..</li>
    <li><strong>Impact:</strong> This latency caused 50% of all customer complaints and revenue loss from abandoned leads.</li>
    <li><strong>Constraint:</strong> Over 90% of our 200+ service providers lacked digital tools, forcing a system solution that was simple for the user but complex in its automation.</li>
  </ul>

  <div class="image-placeholder">
    [Place Image 1 Here: The "Before" State – Chaos and Bottlenecks]
  </div>

 <h2>II. Strategic Pivot: Build vs. Integrate</h2>

  <p>
  The internal development team scoped a custom tool at 6+ months. Recognizing this delay as a strategic business failure, I led a critical pivot: Integrate existing systems to build a Minimum Viable Platform (MVP) in weeks.
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

  <h2>III. Architecture: Workflow Automation via API Backbone</h2>

  <p>
  I architected a solution to automate the entire workflow by leveraging our core Internal Pricing Engine API.
  </p>

<div class="diagram">
  <img src="/assets/img/onlinequotation-flow.png"
       alt="System architecture showing installer PWA, conditional logic engine, internal pricing API, and automated quote email">
</div>


  <ol>
    <li><strong>Frontend Abstraction (PWA):</strong> I implemented a low-code platform as a Progressive Web App (PWA) interface. This solved the 90% adoption issue with a simple, mobile-first experience for providers.</li>
    <li><strong>Smart Rules Engine:</strong> The form was engineered as a dynamic Rules Engine. It parsed inputs (e.g., room size, service type) and acted as a client to call the Internal Pricing Engine API for real-time calculation, eliminating human error.</li>
    <li><strong>API & Workflow Automation:</strong> The process was automated end-to-end:</li>
    <ul>
    <li><strong>Real-Time Pricing:</strong> Data is sent to the Internal Pricing API.</li>
    <li><strong>Data Persistence:</strong> Finalized quote data is logged to the Internal Database via the API integration layer.</li>
    <li><strong>Customer Communication:</strong> An automated engine triggers an instant quote email to the customer.</li>
  </ul>

  </ol>

  <p>
  <strong>The flow:</strong> Installer → PWA → Conditional Logic → Internal Pricing API → Automated Quote Email.
  </p>

 <h2>IV. Quantified Impact and Platform Scaling</h2>

<p> The new system generated immediate, quantifiable results. I personally led the training for all 200+ service providers, ensuring 100% adoption and establishing feedback loops for platform maintenance.</p>

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
      <td>96% Reduction</td>
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

<h2>V. Learnings: Platform Blueprint</h2>

  <ol>
    <li><strong>Technical Debt is Strategic:</strong> Leveraging low-code for the UI while protecting the core Internal API logic was key to delivering $5M in revenue quickly.</li>
    <li><strong>API Integration is Core:</strong> Success hinged on cleanly integrating with the existing Internal Pricing API, creating a scalable blueprint for automating all future service operations.</li>
    <li><strong>Automation Requires Adoption:</strong> Change management and user training are mandatory. A functional system must be readily adopted by its users.</li>
  </ol>

</div>

<div class="divider"></div>
