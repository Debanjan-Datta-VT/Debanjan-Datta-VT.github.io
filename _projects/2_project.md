---
layout: page
title: Parameter Efficient Finetuning for LLM
description: AWS Sagemaker Canvas Enterprise Project Roadmap
importance: 1
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
           
          </p>
        </div>
      </div>
    </div>
  </div>

  <!-- Problem Statement Section -->
  <div class="row mb-4">
    <div class="col-md-3 mb-3">
      <div class="d-flex align-items-center justify-content-center h-100">
        <h3 class="text-primary mb-0">Problem Statement</h3>
      </div>
    </div>
    <div class="col-md-9">
      <div class="card h-100">
        <div class="card-body">
          <p class="card-text">
          The research problem was to find the correct set of hyperparmaters, and training setting for a range of SoTA LLM models to be trained through Parameter Efficient Finetuning (PEFT) methods.
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
          </p>
          <ul class="mt-3">
          <li> Allowing customers to finetune LLM models for business specific problems, with optimized cost and performance. This was part of AWS's managed AutoML offering.</li>
          </ul>
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
            <li> Designed and executed large scale experiments to understand effects of finetuning LLM using PEFT methods (LoRA, qLoRA), to uncover overall performance envelope and investigate failure conditions.</li>
            <li> Deep dived into the hyperparameter landscape for PEFT with multiple methodologies, and performance profiling.</li>
            <li> Analysed performance trade-offs, in applying PEFT on domain specific datasets in resource constrained environments.</li>
            <li> Experimented with multiple distributed paradigns such as FSP, DDP and DP. </li>
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
            <li>Large Language Models</li>
            <li>PEFT</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
