---
title: "Sub-minute probabilistic solar forecasting for real-time stochastic simulations."
collection: publications
category: manuscripts
permalink: /publication/2022-Sub-minute probabilistic solar forecasting
excerpt: '[AI-generated abstract summary] This paper addresses the limitations of current stochastic simulations for solar energy systems, which often fail to reflect high-frequency fluctuations and changing uncertainties in solar power output. It introduces a cutting-edge probabilistic solar forecasting method that enhances real-time simulations. The method combines lasso-penalized quantile regression with an analog-based preselection algorithm, forecasting irradiance over small areas at sub-minute timescales. By using online training, the model updates its parameters and forecasts every few seconds. Despite its computational demands, it completes each forecasting cycle in under one second. Compared to five benchmarking methods, including analog ensemble (AnEn), the proposed method significantly improves forecast accuracy, achieving up to a 55% skill score. The R code and datasets are publicly available on Github to encourage future adoption. '
date: 2022-01-01
venue: 'Renewable and Sustainable Energy Reviews'
link: 'https://doi.org/10.1016/j.rser.2021.111736'
#paperurl: '' #preprint PDF location
#citation: ''
---

<h2> Abstract </h2>
Simulation needs to reflect reality, otherwise, it yields misleading results that are potentially harmful to the operators and decision makers who rely on that simulation. Current stochastic simulation methods for solar energy systems in smart grids mostly consider scenarios generated from a single low-frequency time series, which is unable to reflect the high-frequency fluctuation and changing uncertainty in the actual solar power output. To that end, this paper introduces a state-of-the-art probabilistic solar forecasting method, that provides remedies to the drawbacks, and thus benefits real-time stochastic simulations at large. Lasso-penalized quantile regression is paired with an analog-based preselection algorithm, and is used to forecast the irradiance over a 1 km by 1 km area, in sub-minute timescales. To capture the changing weather condition, the forecasting method uses online training, and updates its parameters and forecasts every few seconds. Despite the heavy computation required, the forecasting method is fast; it takes less than 1 s to complete a forecasting cycle. Through five benchmarking methods, ranging from the naïve climatology and persistence to the state-of-the-art analog ensemble (AnEn), the proposed method is shown to be able to attain an exceptionally high forecast skill in terms of pinball loss (up to a skill score of 55%, with AnEn being the reference model), which is unparalleled by all previous works that used the same dataset. To promote the future uptake of the method, the R code and the final forecast datasets are released on Github.
