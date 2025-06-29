---
title: "Resources"
permalink: /resources/
layout: single
classes: wide
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/resources-banner.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
sidebar:
  nav: "resources"
---

## Platforms

<div class="resources-grid">
  <div class="resource-card">
    <img src="/assets/images/eoh-platform.jpg" alt="Evolution of Heuristics">
    <h3>EoH (Evolution of Heuristics)</h3>
    <p>Platform for optimization, mathematics, machine learning, and more</p>
    <a href="https://github.com/FeiLiu36/EoH" class="btn btn--primary">Visit Platform</a>
  </div>

  <div class="resource-card">
    <img src="/assets/images/openelm-platform.jpg" alt="OpenELM">
    <h3>OpenELM</h3>
    <p>Platform for robots, image, programming puzzles, and more</p>
    <a href="https://github.com/CarperAI/OpenELM" class="btn btn--primary">Visit Platform</a>
  </div>
</div>

## Courses

<div class="resources-list">
  <div class="resource-item">
    <h3>2024 Fall, LLM Agents</h3>
    <p>Course covering LLM basics and LLM for agents</p>
    <a href="https://llmagents-learning.org/f24" class="btn btn--info">Course Website</a>
  </div>
</div>

## Tutorials & Workshops

<div class="resources-list">
  <div class="resource-item">
    <h3>NeurIPS 2023 Workshop: Foundation Models for Decision Making</h3>
    <a href="https://nips.cc/virtual/2023/workshop/66525" class="btn btn--info">Workshop Website</a>
  </div>

  <div class="resource-item">
    <h3>AAAI 2024 Workshop: Public Sector LLMs: Algorithmic and Sociotechnical Design</h3>
    <a href="https://publlm.github.io/" class="btn btn--info">Workshop Website</a>
  </div>

  <div class="resource-item">
    <h3>GECCO 2024 Workshop: Large Language Models for and with Evolutionary Computation (LLMfwEC)</h3>
    <a href="https://sites.google.com/view/llmfwec-2024" class="btn btn--info">Workshop Website</a>
  </div>

  <div class="resource-item">
    <h3>GECCO 2024 Tutorial: Using Large Language Models for Evolutionary Search</h3>
    <a href="https://gecco-2024.sigevo.org/Tutorials" class="btn btn--info">Tutorial Website</a>
    <a href="https://arxiv.org/pdf/2401.07102" class="btn btn--info">Tutorial Report</a>
  </div>
</div>

## Competitions

<div class="resources-list">
  <div class="resource-item">
    <h3>AAAI 2024 Global Competition on Math Problem Solving and Reasoning</h3>
    <a href="https://ai4ed.cc/competitions/aaai2024competition" class="btn btn--info">Competition Website</a>
  </div>

  <div class="resource-item">
    <h3>ICML 2024 Challenges on Automated Math Reasoning</h3>
    <a href="https://sites.google.com/view/ai4mathworkshopicml2024/challenges" class="btn btn--info">Challenge Website</a>
  </div>

  <div class="resource-item">
    <h3>IEEE CIS 2024 Technical Challenge FLAME – 'Fusing Large lAnguage Models with computational intElligence'</h3>
    <a href="https://cis.ieee.org/activities/educational-activites/competitions/flame-technical-challenge-2024" class="btn btn--info">Challenge Website</a>
  </div>
</div>

## Special Issues

<div class="resources-list">
  <div class="resource-item">
    <h3>IEEE TETCI, Special Issue on Neural Architecture Search and Large Machine Learning Models</h3>
    <a href="https://cis.ieee.org/images/files/Documents/call-for-papers/CFP-SI-LMM-final.pdf" class="btn btn--info">Call for Papers</a>
  </div>

  <div class="resource-item">
    <h3>ACM TELO, Special Issue on Integrating Evolutionary Algorithms and Large Language Models</h3>
    <a href="https://dl.acm.org/pb-assets/static_journal_pages/telo/pdf/ACM-CFP-TELO-LLMs-EAs-1717612765163.pdf" class="btn btn--info">Call for Papers</a>
  </div>

  <div class="resource-item">
    <h3>IEEE TEVC, Special Issue on Evolutionary Computation Meets Large Language Models</h3>
    <a href="https://cis.ieee.org/images/files/Documents/call-for-papers/tevc/cfp-ECLLMs-26august2024.pdf" class="btn btn--info">Call for Papers</a>
  </div>

  <div class="resource-item">
    <h3>Engineering, Special Issue on Applications of ChatGPT</h3>
    <a href="https://www.sciencedirect.com/journal/engineering/about/call-for-papers#applications-of-chatgpt" class="btn btn--info">Call for Papers</a>
  </div>
</div>

## Related Collections

<div class="resources-list">
  <div class="resource-item">
    <h3>Awesome LLM</h3>
    <p>Comprehensive collection of LLM resources</p>
    <a href="https://github.com/Hannibal046/Awesome-LLM" class="btn btn--info">Visit Collection</a>
  </div>

  <div class="resource-item">
    <h3>Foundation Models for Combinatorial Optimization</h3>
    <p>Resources on foundation models for combinatorial optimization</p>
    <a href="https://github.com/ai4co/awesome-fm4co" class="btn btn--info">Visit Collection</a>
  </div>

  <div class="resource-item">
    <h3>LLM for Planning</h3>
    <p>Resources on using LLMs for planning tasks</p>
    <a href="https://ai4society.github.io/LLM-Planning-Viz/" class="btn btn--info">Visit Collection</a>
  </div>

  <div class="resource-item">
    <h3>MOO-ML-Papers</h3>
    <p>Collection of papers on multi-objective optimization and machine learning</p>
    <a href="https://github.com/xzhang2523/awesome-moo-ml-papers" class="btn btn--info">Visit Collection</a>
  </div>
</div>

<style>
.resources-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.resource-card {
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  display: flex;
  flex-direction: column;
}

.resource-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.resource-card img {
  width: 100%;
  height: 180px;