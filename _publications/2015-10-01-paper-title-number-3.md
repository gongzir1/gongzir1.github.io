---
title: "	
Production evaluation of citrus fruits based on the yolov5 compressed by knowledge distillation"
collection: publications
category: conferences
permalink: /publication/cscwd
date: 2023-10-01
venue: 'CSCWD'
---

Accurate pre-harvest fruit yield estimation is essential for planning storage, logistics, and pricing in agriculture. However, existing computer vision methods often struggle with small fruit sizes, occlusion by leaves, and overlapping fruits. Moreover, many rely on large, resource-intensive models that are unsuitable for real-world, mobile deployment.

To address these issues, we propose a lightweight and efficient citrus fruit detection and yield estimation framework designed for smartphones. Our method builds on YOLOv5, using MobileNetV2 as a lightweight backbone and integrating an attention mechanism to better detect small and occluded fruits. To further reduce complexity while preserving performance, we apply knowledge distillation, training a compact student model from a larger teacher model.

Finally, we use a linear regression model to estimate fruit production based on the detected fruit count. Experiments show that our approach achieves accurate fruit detection and yield estimation, making it a practical tool for on-site agricultural use.
