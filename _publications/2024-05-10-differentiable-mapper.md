---
title: "Differentiable Mapper for Topological Optimization of Data Representation"
collection: publications
permalink: /publication/2024-05-10-differentiable-mapper
message: 'Now accepted at ICML 2024!'
excerpt:   'The Mapper algorithm has been known to be a powerful tool in visualization and data analytics, but suffers from dependence on many hand-turning parameters. In this work, we propose a relaxation and generalization of the Mapper so that the parameters can be optimized using gradient descent. Convergence results and applications are also provided.'
date: 2024-02-20
venue: "Forty-first International Conference on Machine Learning"
paperurl: 'https://arxiv.org/pdf/2402.12854'
citation: #'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

Unsupervised data representation and visualization using tools from topology is an active and growing field of Topological Data Analysis (TDA) and data science. Its most prominent line of work is based on the so-called Mapper graph, which is a combinatorial graph whose topological structures (connected components, branches, loops) are in correspondence with those of the data itself. While highly generic and applicable, its use has been hampered so far by the manual tuning of its many parameters-among these, a crucial one is the so-called filter: it is a continuous function whose variations on the data set are the main ingredient for both building the Mapper representation and assessing the presence and sizes of its topological structures. However, while a few parameter tuning methods have already been investigated for the other Mapper parameters (i.e., resolution, gain, clustering), there is currently no method for tuning the filter itself. In this work, we build on a recently proposed optimization framework incorporating topology to provide the first filter optimization scheme for Mapper graphs. In order to achieve this, we propose a relaxed and more general version of the Mapper graph, whose convergence properties are investigated. Finally, we demonstrate the usefulness of our approach by optimizing Mapper graph representations on several datasets, and showcasing the superiority of the optimized representation over arbitrary ones.
The associated Github repository can be found [here](https://github.com/ZiyadOulhaj/Mapper-Optimization).
