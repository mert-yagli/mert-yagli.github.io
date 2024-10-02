---
title: "Non-crossing quantile regression neural network as a calibration tool for ensemble weather forecasts"
collection: publications
category: manuscripts
permalink: /publication/2024-Non-crossing quantile regression
excerpt: '[AI-generated abstract summary] The study tackles under-dispersion and quantile crossing in ensemble numerical weather prediction (NWP) by introducing a non-crossing quantile regression neural network (NCQRNN). This method ensures reliable forecasts without crossing by using a special hidden layer. In a solar irradiance case study, NCQRNN outperformed other models, offering sharp and calibrated forecasts. Its simple design can be broadly applied to various neural networks. '
date: 2024-03-01
venue: 'Advances in Atmospheric Sciences'
link: 'https://doi.org/10.1007/s00376-023-3184-5'
#paperurl: 'https://doi.org/10.1007/s00376-023-3184-5'
#citation: 'Song, Mengmeng, Dazhi Yang, Sebastian Lerch, Xiang’ao Xia, Gokhan Mert Yagli, Jamie M. Bright, Yanbo Shen, Bai Liu, Xingli Liu, and Martin János Mayer. "Non-crossing quantile regression neural network as a calibration tool for ensemble weather forecasts." Advances in Atmospheric Sciences (2024): 1-21.'
---

<h2> Abstract </h2>
Despite the maturity of ensemble numerical weather prediction (NWP), the resulting forecasts are still, more often than not, under-dispersed. As such, forecast calibration tools have become popular. Among those tools, quantile regression (QR) is highly competitive in terms of both flexibility and predictive performance. Nevertheless, a long-standing problem of QR is quantile crossing, which greatly limits the interpretability of QR-calibrated forecasts. On this point, this study proposes a non-crossing quantile regression neural network (NCQRNN), for calibrating ensemble NWP forecasts into a set of reliable quantile forecasts without crossing. The overarching design principle of NCQRNN is to add on top of the conventional QRNN structure another hidden layer, which imposes a non-decreasing mapping between the combined output from nodes of the last hidden layer to the nodes of the output layer, through a triangular weight matrix with positive entries. The empirical part of the work considers a solar irradiance case study, in which four years of ensemble irradiance forecasts at seven locations, issued by the European Centre for Medium-Range Weather Forecasts, are calibrated via NCQRNN, as well as via an eclectic mix of benchmarking models, ranging from the naïve climatology to the state-of-the-art deep-learning and other non-crossing models. Formal and stringent forecast verification suggests that the forecasts post-processed via NCQRNN attain the maximum sharpness subject to calibration, amongst all competitors. Furthermore, the proposed conception to resolve quantile crossing is remarkably simple yet general, and thus has broad applicability as it can be integrated with many shallow- and deep-learning-based neural networks.
