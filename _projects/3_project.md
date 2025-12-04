---
layout: page
title: Time Series Anomaly Detection
description: AWS Lookout for Metrics Service Enhancement
importance: 2
category: AWS Project
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
            Enhanced AWS Lookout for Metrics anomaly detection service by improving customer interpretability and evaluating detection accuracy while maintaining real-time, low-latency performance guarantees.
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
            When my team took over ownership of AWS Lookout for Metrics, an anomaly detection service, we inherited two key challenges: customers struggled to understand our anomaly scores, and the service had some performance gaps. I was tasked with investigating improvement opportunities across both customer experience and detection accuracy, while ensuring we maintained our real-time, low-latency service guarantees.
          </p>  
        </div>
      </div>
    </div>
  </div>

  <!-- Business Impact Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-success mb-0">Business Impact</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <p class="card-text">
            The score normalizer was successfully launched to production and significantly improved customer satisfaction—customers could now interpret what the anomaly scores meant, which was one of our primary pain points. This directly addressed the interpretability complaints we'd been receiving from enterprise customers using AWS Lookout for Metrics for business-critical monitoring applications.
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Technical Details Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-info mb-0">Technical Details & Contributions</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <ul class="list-unstyled">
            <li><strong>Algorithm Evaluation:</strong> Benchmarked RCF alternatives (dilated 1-D CNNs, Matrix Profile) against latency SLA and internal datasets.</li>
            <li><strong>Evaluation Framework:</strong> Implemented Point-Adjusted Precision/Recall metrics for comprehensive point and range anomaly detection evaluation.</li>
            <li><strong>Score Normalizer:</strong> Designed novel ensemble-based normalizer using data sketches to transform raw RCF scores into interpretable percentile values.</li>
            <li><strong>Statistical Validation:</strong> Validated normalizer robustness through rigorous testing (qualitative and quantitative) for production deployment.</li>
            <li><strong>Change-Point Detection:</strong> Developed online detector using ACF and Matrix Profile for enhanced time series shift detection.</li>
            <li><strong>Dataset Expansion:</strong> Integrated UCR time series data to strengthen benchmarking capabilities.</li>
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
          <ul class="list-unstyled">
            <li>Time Series Anomaly Detection</li>
            <li>Matrix Profile</li>
            <li>Change-Point Detection</li>
            <li>AWS Lookout for Metrics</li>
          </ul>
        </div>
      </div>
    </div>
  </div>

</div>
