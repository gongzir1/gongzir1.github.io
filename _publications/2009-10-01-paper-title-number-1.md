---
title: "Not All Edges are Equally Robust: Evaluating the Robustness of Ranking-Based Federated Learning"
collection: publications
category: conferences
permalink: /publication/ieeesp
date: 2025-10-01
venue: 'IEEE Symposium on Security and Privacy (S&P)'
citation: 'Gong, Zirui, et al. "Not All Edges are Equally Robust: Evaluating the Robustness of Ranking-Based Federated Learning." arXiv preprint arXiv:2503.08976 (2025).'
---
Federated Ranking Learning (FRL) is a state-of-the-art FL framework that stands out for its communication efficiency and resilience to poisoning attacks. It diverges from the traditional FL framework in two ways: 1) it leverages discrete rankings instead of gradient updates, significantly reducing communication costs and limiting the potential space for malicious updates, and 2) it uses majority voting on the server side to establish the global ranking, ensuring that individual updates have minimal influence since each client contributes only a single vote. These features enhance the system's scalability and position FRL as a promising paradigm for FL training.
However, our analysis reveals that FRL is not inherently robust, as certain edges are particularly vulnerable to poisoning attacks. Through a theoretical investigation, we prove the existence of these vulnerable edges and establish a lower bound and an upper bound for identifying them in each layer. Based on this finding, we introduce a novel local model poisoning attack against FRL, namely the Vulnerable Edge Manipulation (VEM) attack. The VEM attack focuses on identifying and perturbing the most vulnerable edges in each layer and leveraging an optimization-based approach to maximize the attack's impact. Through extensive experiments on benchmark datasets, we demonstrate that our attack achieves an overall 53.23% attack impact and is 3.7x more impactful than existing methods. Our findings highlight significant vulnerabilities in ranking-based FL systems and underline the urgency for the development of new robust FL frameworks.

<a href="https://gongzir1.github.io/vem.github.io/" target="_blank">
  <button style="padding: 8px 16px; font-size: 16px; background-color: #007acc; color: white; border: none; border-radius: 5px; cursor: pointer;">
    Learn More
  </button>
</a>
