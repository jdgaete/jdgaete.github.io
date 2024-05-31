---
layout: page
title: Black-Box Adversarial Attacks Against Models of Code
description: Model of CodeImplemented and analyzed a generalizable black-Box adversarial attack against models of code
img: assets/img/black-box.jpg
importance: 2
category: work
related_publications: false
---

Models of code have shown impressive results for analyzing, understanding and even writing codes. As a consequence, they have the potential to automate software engineering tasks involving code comprehension and generation. However, it is important to ask: are they safeguarded against adversarial attacks? Attacks on such models using small perturbations can pose a big challenge and can highly impact the accuracy of their results, forcing research in the direction that aims to improve the robustness of these methods. In order to test if these models are vulnerable to adversarial attacks, we focused our attack on models that attempt to predict the function name for code snippets (what the code is doing). We take our inspiration from the work by Yefet et al., 2019, which proposes adversarial attack for a similar setting but focuses on white-box attack. We’ll instead focus primarily on black-box attack.

[CODE](https://github.com/lamhagoel/adversarial-examples)
[REPORT](https://github.com/lamhagoel/adversarial-examples/blob/master/AdvAttackModelsOfCode.pdf)