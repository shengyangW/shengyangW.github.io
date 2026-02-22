---
title: "Interpretable Detection and Localization of False Data Injection Attacks Based on Causal Learning"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'This paper propose a causal learning structure to quantify the casuality between measurements and locate the measurements under cyber attacks based on the causality anomalies.'
date: 2023-09-25
venue: '2023 IEEE Power & Energy Society General Meeting (PESGM)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10253166'
---

False Data Injection Attack (FDIA) has become a growing concern for modern cyber-physical power systems. Existing data-driven FDIA detection methods are typically based on identifying abnormal spatiotemporal correlation patterns in measurement data, whose accuracy may degrade with the continuous drift of data distributions over the long-term application. In addition, the use of black-box models with bad interpretability may make it difficult to precisely locate manipulated measurements. This paper proposes a bi-level framework based on causal learning to detect and locate FDIAs. The lower level applies a causal inference algorithm, X-Learner, to generate causality matrices to unveil causal relationships between different measurements. The upper level then utilizes a spectral-embedded one-class support vector machine to detect FDIAs and a calibrated eigenvector centrality metric to identify attacked measurements. Compared with correlation analysis, causal learning is more robust against the variation of data distributions as it detects FDIAs based on highly abstracted physical causality. Besides, thanks to the inherent topological implication of causality matrices, causal learning also exhibits stronger potential in FDIA localization. The performance of the proposed framework is validated through experiments on the IEEE 39-bus system.
