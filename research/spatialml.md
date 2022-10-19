---
layout: default
title: Spatial Machine Learning
parent: Research
nav_order: 3
---

Machine and Deep learning models for spatial data analysis are also being actively studied, and random forest is one of the popular techniques that are frequently used on spatial prediction. [Dr. Zhengyuan Zhu](https://scholar.google.com/citations?view_op=list_works&hl=en&user=ixDds0sAAAAJ), [Dr. Daniel Nettleton](https://scholar.google.com/citations?user=5TdAL2cAAAAJ&hl=en), and I proposed a generalized version of out-of-bag guided random forest prediction intervals, which is well-adapted for spatially dependent data [spRFPI](https://github.com/junpeea/spRFPI). We adopted dependency-adjusted regression tree (DART) node-splitting idea and developed a novel non-parametric kernel out-of-bag estimator to estimate the underlying conditional prediction error distribution. Theoretical results on the asymptotic consistency of our approach are well-established. Empirical simulation studies and some real data applications indicate that our proposed prediction interval provides good coverage, and is generally more efficient than existing approaches when observations are spatially dependent. 

We are now investigating in efficient active learning designs under the random forest regression framework. We construct a distance measure using the proximity measure of a random forest, and we improve the prediction model performance by selecting tree-balanced observations even under a certain class of covariate-shift. Based on these academic achievements and practical experiences, I would like to construct the future research work that develops and advances various types of methodologies that uses the state-of-art algorithms and techniques in statistical learning for spatially dependent data.

## Random Forest Prediction Interval for Spatial data
Paper  link : (working in progress)\
Github link : [spRFPI](https://github.com/junpeea/spRFPI)\
Abstract :\
Random forest is a popular machine learning technique that is often used on spatial data for prediction. However, in practice, the spatial dependence of a response variable has typically been ignored in constructing prediction intervals with random forest algorithms, which may result in either low accuracy or low efficiency in such applications. We propose a generalized version of out-of-bag guided random forest prediction intervals, which is well-adapted for spatially dependent data. We use dependency-adjusted regression tree (DART) node-splitting and a novel non-parametric kernel out-of-bag estimator to estimate the underlying conditional prediction error distribution. Theoretical results on the asymptotic consistency of our approach are obtained. Empirical simulation studies and the analysis of global earthquake data indicate that our proposed prediction interval provides good coverage, and is generally more efficient than  existing approaches when observations are spatially dependent.

## An Efficient Active Learning Design through Random Forest under Covariate Shift
Paper  link : (working in progress)\
Github link : (working in progress)
