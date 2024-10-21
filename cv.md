---
title: 
feature_text: |
   
feature_image: "../assets/banner/banner_github.jpg"
aside: true
---
<!-- Style for the timeline with right-aligned location/duration and boxed content -->
<style>
  .timeline {
    display: flex;
    flex-direction: column;
    margin-left: 50px;
    margin-bottom: 40px;
  }

  .timeline-item {
      display: flex;
      align-items: flex-start;
      margin-bottom: 40px;
      position: relative;
  }

  .timeline-info {
      width: 150px;
      margin-right: 20px;
      text-align: right;
  }

  .timeline-marker {
      position: relative;
      margin-right: 20px;
  }

  .timeline-marker::before {
      content: '';
      position: absolute;
      top: 0;
      left: 50%;
      width: 12px;
      height: 12px;
      border-radius: 50%;
      background-color: #05BF85;
      border: 2px solid #fff;
      box-shadow: 0 0 0 2px #05BF85;
      transform: translateX(-50%);
      z-index: 2;
  }

  .timeline-marker::after {
      content: '';
      position: absolute;
      top: 12px; /* Start just below the dot */
      left: 50%;
      width: 2px;
      bottom: -40px; /* Extend slightly beyond the end of the item */
      background-color: #05BF85;
      transform: translateX(-50%);
      z-index: 0;
  }

  .timeline-item:last-child .timeline-marker::after {
      display: none;
  }

  .timeline-content {
      flex-grow: 1;
      background-color: #eafaf1;
      border: 0px solid #ccc;
      padding: 15px;
      position: relative;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      width: 100%;
      z-index: 1;
  }

  .timeline-content ul {
      list-style-type: disc;
      padding-left: 20px;
      margin: 0;
  }

  .timeline-content ul li {
      margin-bottom: 5px;
  }

  .timeline-content h4 {
      margin: 0 0 5px 0;
      color: #2c3e50;
  }

  .timeline-content h5 {
      margin: 0 0 10px 0;
      color: #777;
  }

</style>


<!-- Professional Timeline -->
<div class="timeline-section">
  <div class="section-header"><h3>Professional Timeline</h3></div>
  <div class="timeline">
    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Max Planck Institute</div>
        <div>2020/10 - Present</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>PhD Researcher</h4>
        <h5>Projects</h5>
        <ul>
          <li>Adversarial collaboration between GNWT and IIT</li>
          <li>iEEG data documentation and BIDS conversion</li>
          <li>Conscious experience timing (dual-task paradigm)</li>
          <li>Bayesian evidence accumulation for iEEG data</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Max Planck Institute</div>
        <div>2019/08 - 2020/09</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>Lab Manager</h4>
        <h5>Projects</h5>
        <ul>
          <li>Design of experimental paradigms for pilot studies</li>
          <li>Collection of behavioral and eyetracking data</li>
          <li>Data analysis for various projects</li>
          <li>Organization of lab meetings and events</li>
        </ul>
      </div>
    </div>
  </div>
</div>

<!-- Education Timeline -->
<div class="timeline-section">
  <div class="section-header"><h3>Education Timeline</h3></div>
  <div class="timeline">
    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Donders Institute | Radboud University</div>
        <div>2020 - Present</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>PhD studies</h4>
        <h5>Thesis</h5>
        <ul>
          <li>Temporal Crossroads: Probing the dynamics of experience to refine theories of consciousness</li>
        </ul>
        <h5>Projects</h5>
        <ul>
          <li>REVIEW: The search for the neural correlate of consciousness: Progress and challenges</li>
          <li>ARC-COGITATE: An adversarial collaboration to critically evaluate theories of consciousness</li>
          <li>TESTING FRAMEWORK: A standardized framework to test event-based experiments</li>
          <li>DATA SET: Open multi-center iEEG dataset with task probing conscious visual perception</li>
          <li>PRP: Investigating the timing of conscious experience using a dual-task paradigm and quantified introspection</li>
          <li>METHODS: Variational Representation Similarity Analysis (vRSA) for EEG/MEG</li>
        </ul>
      </div>
    </div>

  <div class="timeline">
    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Georg August Universitaet</div>
        <div>2016 - 2019</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>M.Sc. Developmental, Neural, and Behavioral Biology</h4>
        <h5>Thesis and Projects</h5>
        <ul>
          <li>Thesis: Assessing the role of low-level features in associative learning of valence</li>
          <li>Design and analysis of EEG data for 24 subjects</li>
          <li>Pre-registration and replication with an additional 24 EEG subjects</li>
        </ul>
      </div>
    </div>

    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Universite Angers</div>
        <div>2013 - 2016</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>B.Sc. Organism and Population Biology</h4>
      </div>
    </div>

    <div class="timeline-item">
      <!-- Right-aligned Location and Duration Column -->
      <div class="timeline-info">
        <div>Lycee Lavoisier</div>
        <div>2012</div>
      </div>
      <!-- Dot and Line -->
      <div class="timeline-marker"></div>
      <!-- Role and Project Column with Box -->
      <div class="timeline-content">
        <h4>Baccalaureat Scientifique</h4>
      </div>
    </div>
  </div>
</div>

<h2 style="font-weight: bold;">Miscellaneous</h2>
<ul style="list-style-type: disc; padding-left: 20px;">
  <li>Languages: French (fluent/native), English (fluent), German (fluent)</li>
</ul>
