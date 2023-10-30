---
title: "Simple Transferability Estimation for Regression Tasks"
collection: publications
permalink: /publications/UAI-2023-simple-transferability
excerpt: 'We introduce a family of simple, yet effective transferability estimators to predict the transfer learning performance between two regression tasks.'
date: 2023-08-01
venue: '39th Conference on Uncertainty in Artificial Intelligence (UAI)'
---
Abstract:
We consider transferability estimation, the problem of estimating how well deep learning models
transfer from a source to a target task. We focus on regression tasks, which received little previous attention, and propose two simple and computationally efficient approaches that estimate transferability based on the negative regularized mean squared error of a linear regression model. We prove novel theoretical results connecting our approaches to the actual transferability of the optimal target models obtained from the transfer learning process. Despite their simplicity, our approaches significantly outperform existing state-of-the-art regression transferability estimators in both accuracy and efficiency. On two large-scale keypoint regression benchmarks, our approaches yield 12% to 36% better results on average while being at least 27% faster than previous state-of-the-art methods. [Paper Link](https://openreview.net/pdf?id=1g1zg2dgIH)

A shorter version was published at NeurIPS 2022 Workshop on Distribution Shifts ([DistShift](https://sites.google.com/view/distshift2022))
