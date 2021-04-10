---
title: "Visualization of biomedical and genomic data"
index: 3
tags:  
  - "genomic visualization"
  - "interactive false discovery"
  - "time-based data"
  - "data visualization"  
categories:
  - "Genomic visualization"
copyright: "CoLabo 2021"
---

New genomic experimental techniques generate not only very large datasets, but also highly dynamic data that changes over time. We aim at creating novel visualization tools that allow to explore these datasets and generate hypothesis of time-based processes, such as regulatory networks and single-cell gene expression data. We are interested in developing new technologies that facilitate interactive exploration as part of larger data analysis pipelines, while based on rigorous statistical foundations to quantify the possibility of false discoveries during this exploration.

<!--more-->

4 – Dynamic multiple hypothesis correction in interactive visualization: We need novel approaches to reduce biases and better understand the models derived from large biomedical datasets. One problem that is gaining recognition among specialists is that of biases due to exploratory analysis (Gotz et al., ACM Trans Interact Intell 2017). Interactive visualization can lead to insights from complex datasets, however, it also makes it very easy to implicitly test a vast number of statistical hypothesis (e.g.: are pairs of variables correlated, are the means of two distributions the same), with the corresponding increasing chance of false discoveries that affect the subsequent analysis and modeling processes. I have conducted initial work on this issue with my tool Mirador, and my plan is to investigate it further by developing statistical formalisms to measure the false discovery rates associated with different types of interactive visualizations, and designing interaction methodologies to keep users aware of possible false discoveries. I find the question of “how interfaces for data visualization can be quantified in terms of their statistical effects in model building” to be a very relevant and exciting problem, since it sits squarely at the intersection of machine learning, data visualization, and user interface design. Working with popular frameworks for visualization and computational design, such as Processing and D3, will allow me to maximize the reach of my research to audiences of experts and beginners alike. Therefore, I plan to maintain a robust involvement with those projects, hoping to contribute to their development and incorporate features implementing new methods and interfaces created in my lab.