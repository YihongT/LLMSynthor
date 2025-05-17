# <img src="resources/icon.png" alt="LLMSynthor Icon" width="80" style="vertical-align: middle; margin-right: 8px;"/> LLMSynthor


This is the **official repository** for the paper _"Large Language Models for Data Synthesis."_  

📚 [[ArXiv](https://arxiv.org/abs/)] • 🌐 [[Project Page](https://yihongt.github.io/llmsynthor_web/)]

---

## 📝 Abstract

Generating synthetic data that faithfully captures the statistical structure of real-world distributions is a fundamental challenge in data modeling. Classical approaches often depend on strong parametric assumptions or manual structural design and struggle in high-dimensional or heterogeneous domains. Recent progress in Large Language Models (LLMs) reveals their potential as flexible, high-dimensional priors over real-world distributions. However, when applied to data synthesis, standard LLM-based sampling is inefficient, constrained by fixed context limits, and fails to ensure statistical alignment. Given this, we introduce LLMSynthor, a general framework for data synthesis that transforms LLMs into structure-aware simulators guided by distributional feedback. LLMSynthor treats the LLM as a nonparametric copula simulator for modeling high-order dependencies and introduces \emph{LLM Proposal Sampling} to generate grounded proposal distributions that improve sampling efficiency without requiring rejection. By minimizing discrepancies in the summary statistics space, the iterative synthesis loop aligns real and synthetic data while gradually uncovering and refining the latent generative structure.
We evaluate LLMSynthor in both controlled and real-world settings using heterogeneous datasets in privacy-sensitive domains (e.g., e-commerce, population, and mobility) that encompass both structured and unstructured formats. The synthetic data produced by LLMSynthor shows high statistical fidelity, practical utility, and cross-data adaptability, positioning it as a valuable tool across economics, social science, urban studies, and beyond. 


---

## 🚧 TODO

- [ ] Code release scheduled by **end of June 2025**

Stay tuned for updates!

---

## License

This project will be released under an open-source license upon publication.
