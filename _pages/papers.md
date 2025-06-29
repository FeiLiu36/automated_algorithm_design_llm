---
title: "Research Papers"
permalink: /papers/
layout: single
classes: wide
author_profile: false
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/papers-banner.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
sidebar:
  nav: "papers"
---

## Latest Publications

<div class="publications-grid">
  <div class="publication-card">
    <img src="/assets/images/paper1.jpg" alt="Algorithm Evolution using Large Language Model">
    <h3>Algorithm Evolution using Large Language Model</h3>
    <p>Liu et al. (2023)</p>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2311.15249" class="btn btn--small btn--info">Paper</a>
      <a href="https://github.com/FeiLiu36/eoh" class="btn btn--small btn--info">Code</a>
    </div>
  </div>

  <div class="publication-card">
    <img src="/assets/images/paper2.jpg" alt="Evolution of Heuristics">
    <h3>Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model</h3>
    <p>Liu et al. (2024) - ICML 2024 (Oral)</p>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2401.02051" class="btn btn--small btn--info">Paper</a>
      <a href="https://github.com/FeiLiu36/EoH" class="btn btn--small btn--info">Code</a>
    </div>
  </div>

  <div class="publication-card">
    <img src="/assets/images/paper3.jpg" alt="ReEvo">
    <h3>ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution</h3>
    <p>Authors et al. (2024) - NeurIPS 2024</p>
    <div class="publication-links">
      <a href="https://arxiv.org/abs/2402.01145" class="btn btn--small btn--info">Paper</a>
      <a href="https://github.com/ai4co/LLM-as-HH" class="btn btn--small btn--info">Code</a>
    </div>
  </div>
</div>

## Paper Categories

### Review Papers

| Title                                                        | Publication      | Code | Paper                                        |
| ------------------------------------------------------------ | ---------------- | ---- | -------------------------------------------- |
| Evolutionary Computation in the Era of Large Language Model: Survey and Roadmap | Arxiv, Jan 2024  | -    | [paper](https://arxiv.org/abs/2401.10034)    |
| A Survey of Neural Code Intelligence: Paradigms, Advances and Beyond | Arxiv, Mar. 2024 | -    | [paper](https://arxiv.org/abs/2403.14734)    |
| When Large Language Model Meets Optimization                 | Arxiv, May 2024  | -    | [paper](http://www.arxiv.org/pdf/2405.10098) |
| A Systematic Survey on Large Language Models for Algorithm Design | Arxiv, Oct 2024  | -    | [paper](https://arxiv.org/abs/2410.14716)    |

### Algorithm/Heuristic/Function Search

| Title                                                        | Publication      | Code                                                 | Paper                                                       |
| ------------------------------------------------------------ | ---------------- | ---------------------------------------------------- | ----------------------------------------------------------- |
| Hypothesis Search: Inductive Reasoning with Language Models  | ICLR 2024        | -                                                    | [paper](https://arxiv.org/abs/2309.05660)                   |
| ToolChain*: Efficient Action Space Navigation in Large Language Models with A* Search | ICLR 2024        | -                                                    | [paper](https://arxiv.org/abs/2310.13227)                   |
| Algorithm Evolution using Large Language Model               | Arxiv 2023       | [code](https://github.com/FeiLiu36/eoh)              | [paper](https://arxiv.org/abs/2311.15249)                   |
| Mathematical discoveries from program search with large language models | Nature           | [code](https://github.com/google-deepmind/funsearch) | [paper](https://www.nature.com/articles/s41586-023-06924-6) |
| Evolution of Heuristics: Towards Efficient Automatic Algorithm Design Using Large Language Model | ICML 2024 (Oral) | [code](https://github.com/FeiLiu36/EoH)              | [paper](https://arxiv.org/abs/2401.02051)                   |
| ReEvo: Large Language Models as Hyper-Heuristics with Reflective Evolution | NeurIPS 2024     | [code](https://github.com/ai4co/LLM-as-HH)           | [paper](https://arxiv.org/abs/2402.01145)                   |

### LLM as Optimizer

| Title                                                        | Publication      | Code                                            | Paper                                     |
| ------------------------------------------------------------ | ---------------- | ----------------------------------------------- | ----------------------------------------- |
| Large Language Models as Optimizers                          | Arxiv, Sep 2023  | [code](https://github.com/google-deepmind/opro) | [paper](https://arxiv.org/abs/2309.03409) |
| Large language model for multi-objective evolutionary optimization | Arxiv, Oct. 2023 | [code](https://github.com/FeiLiu36/LLM4MOEA)    | [paper](https://arxiv.org/abs/2310.12541) |
| Large Language Models as Evolutionary Optimizers             | Arxiv, Oct. 2023 | -                                               | [paper](https://arxiv.org/abs/2310.19046) |
| Using Large Language Models for Hyperparameter Optimization  | NeurIPS 2023     | -                                               | [paper](https://arxiv.org/abs/2312.04528) |

<style>
.publications-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.publication-card {
  border: 1px solid #e0e0e0;
  border-radius: 8px;
  overflow: hidden;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.publication-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 20px rgba(0,0,0,0.1);
}

.publication-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.publication-card h3 {
  padding: 1rem 1rem 0.5rem;
  margin: 0;
  font-size: 1.2rem;
}

.publication-card p {
  padding: 0 1rem;
  color: #666;
  margin: 0 0 1rem;
}

.publication-links {
  padding: 0 1rem 1rem;
  display: flex;
  gap: 0.5rem;
}

.btn--small {
  padding: 0.3rem 0.6rem;
  font-size: 0.8rem;
}

table {
  width: 100%;
  margin-bottom: 2rem;
  border-collapse: collapse;
}

th, td {
  padding: 0.75rem;
  border-bottom: 1px solid #e0e0e0;
}

th {
  background-color: #f8f9fa;
  text-align: left;
}

tr:hover {
  background-color: #f8f9fa;
}
</style>