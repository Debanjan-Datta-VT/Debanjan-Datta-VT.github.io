---
layout: page
title: Automated ML Pipeline Creator
description: Chat-based ML Service with Automated Pipeline Generation
importance: 2
category: Amazon Web Services
related_publications: true
---

<div class="container-fluid"> 
  <!-- Project Overview Section -->
  <div class="row mb-4">
    <div class="col-12">
      <div class="card">
        <div class="card-body">
          <h2 class="card-title text-center mb-4">Project Overview</h2>
          <p class="lead text-center">
            Designed and developed a backend automated ML pipeline creator for a managed ML service that enables business users to solve problems through a chat-based interface, featuring robust data preprocessing, automated feature engineering, and customizable pipeline sequencing.
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Problem Statement Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-primary mb-0">Situation & Context</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <p class="card-text">
            Our managed ML service wanted a chat-based product which would support business users bringing in problems and solving them using ML. My responsibility was designing and developing the backend automated ML pipeline creator that would preprocess data and train ML models. Existing out-of-the-box AutoML solutions like AutoGluon were memory intensive and slower due to ensembles and meta-learning approaches, requiring a more efficient solution.
          </p>  
        </div>
      </div>
    </div>
  </div>

  <!-- Task Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-warning mb-0">Task</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <div class="mb-3">
            <h5 class="text-primary">Phase 1: Automated ML Pipeline Builder</h5>
            <ul class="list-group list-group-flush ms-3">
              <li class="list-group-item">Develop automated ML pipeline with best practices, reproducibility, and low latency</li>
              <li class="list-group-item">Handle extremely noisy data with mixed types and inconsistent formats</li>
              <li class="list-group-item">Perform advanced data type detection and task type detection</li>
              <li class="list-group-item">Implement automated feature engineering</li>
              <li class="list-group-item">Enforce user-driven training time limits</li>
            </ul>
          </div>
          <div>
            <h5 class="text-primary">Phase 2: Customizable Pipeline Sequencing</h5>
            <ul class="list-group list-group-flush ms-3">
              <li class="list-group-item">Allow users to customize ML pipeline by choosing from operations</li>
              <li class="list-group-item">Automatically determine correct sequence of transformations</li>
              <li class="list-group-item">Ensure proper ordering to prevent unintended perturbations</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Action/Implementation Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-info mb-0">Action & Implementation</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <div class="mb-3">
            <h5 class="text-success">Phase 1 Implementation</h5>
            <ul class="list-group list-group-flush">
              <li class="list-group-item"><strong>Framework Development:</strong> Created framework extending scikit-learn with open source libraries, supporting multiple models with XGBoost as default</li>
              <li class="list-group-item"><strong>Training Time Enforcement:</strong> Modified XGBoost's internal training loop using callbacks to accurately track training time and gracefully exit</li>
              <li class="list-group-item"><strong>Robust Data Type Detection:</strong> Developed heuristic using data statistics and practical thresholds that worked in edge cases where pandas would fail</li>
              <li class="list-group-item"><strong>LLM-powered Feature Engineering:</strong> Implemented chained 2-step method: candidate feature logic generation, then code generation with multiple trials and checks</li>
              <li class="list-group-item"><strong>Large-scale Testing:</strong> Created benchmark with over 300 datasets for comprehensive evaluation</li>
            </ul>
          </div>
          <div>
            <h5 class="text-success">Phase 2 Implementation</h5>
            <ul class="list-group list-group-flush">
              <li class="list-group-item"><strong>Transform Analysis:</strong> Surveyed prior works and analyzed situations where incorrect ordering would cause issues</li>
              <li class="list-group-item"><strong>Partial Order Development:</strong> Established ordering rules (e.g., standardization before dropping missing values, normalization before oversampling)</li>
              <li class="list-group-item"><strong>Transform Matrix:</strong> Created matrix of transforms and meta-characteristics describing prerequisites and post-effects</li>
              <li class="list-group-item"><strong>Rule-based Algorithm:</strong> Developed topological ordering algorithm ensuring correct transform sequencing</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- Results Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-success mb-0">Results & Impact</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <ul class="list-group list-group-flush">
            <li class="list-group-item"><strong>Superior Performance:</strong> Data type detection heuristic outperformed competing state-of-the-art baselines, especially AutoGluon</li>
            <li class="list-group-item"><strong>Improved Efficiency:</strong> Achieved better latency than competing baselines while maintaining comparable performance</li>
            <li class="list-group-item"><strong>Simplified Effectiveness:</strong> Demonstrated that standard ML pipeline with XGBoost was simple yet effective approach</li>
            <li class="list-group-item"><strong>Successful Launch:</strong> Product was successfully launched with Phase 1 implementation in production</li>
            <li class="list-group-item"><strong>Business Impact:</strong> Enabled business users to leverage ML through intuitive chat interface without requiring ML expertise</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

  <!-- Keywords -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-info mb-0">Keywords</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <ul class="list-group list-group-flush">
            <li class="list-group-item">Automated Machine Learning (AutoML)</li>
            <li class="list-group-item">ML Pipeline Automation</li>
            <li class="list-group-item">Feature Engineering</li>
            <li class="list-group-item">XGBoost Optimization</li>
            <li class="list-group-item">Data Type Detection</li>
            <li class="list-group-item">Transform Sequencing</li>
            <li class="list-group-item">LLM-powered Code Generation</li>
            <li class="list-group-item">Scikit-learn Framework</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

</div>
