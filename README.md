# Causal-Papers-Code
Repo to track interesting papers, articles, and code

## Table of Contents

[1. Literature](#literature)

[2. Articles](#articles)

[3. Code](#code)

## Literature

### How to conduct and report online platform studies
- https://www.sciencedirect.com/science/article/pii/S0167811624001149

Note: Studies lack true random assignment of ads to consumers, preventing causal inference. A review of 133 published online platform studies revea these studies are mistakenly presented as (randomized) experiments. If you understand where the randomization occurs (group assignment, not ad impressions), you can get valid learnings. 

### Black Box Causal Inference: Effect Estimation via Meta Prediction
- https://arxiv.org/abs/2503.05985

Note: frames causal inference as a dataset-level prediction problem, offloading algorithm design to the learning process

### How Much Should We Trust Staggered Difference-In-Differences Estimates?
- https://www.hbs.edu/ris/Publication%20Files/21-112_8a5a4ab3-b9e7-447d-a0fe-a504b3890fb9.pdf

### Quantiles in Nonrandom Samples and Observational Studies
- https://www.jstor.org/stable/2291534

### Potential Outcome and Directed Acyclic Graph Approaches to Causality
- https://arxiv.org/pdf/1907.07271

### Learning Causal Effects From Observational Data in Healthcare: A Review and Summary
- https://www.frontiersin.org/journals/medicine/articles/10.3389/fmed.2022.864882/pdf

Thoughts: properly classifies causal inference frameworks and models based on their intervention applications with respect to population size. The table and flowchart below serve as a memory refresher and quick reference guide for anyone learning causal inference

### Constraint-based causal discovery with tiered background knowledge and latent variables in single or overlapping datasets
- https://arxiv.org/pdf/2503.21526

Idea: temporal causal discovery across overlapping datasets, even with latent variables.

### DeCaFlow: A Deconfounding Causal Generative Model
- https://arxiv.org/pdf/2503.15114

Thoughts: model can identify queries impacted by hidden confounding using a number of strategies, including proximal inference

### Bayesian A/B Testing at VWO
- https://vwo.com/downloads/VWO_SmartStats_technical_whitepaper.pdf

Idea: A white paper that discusses an idea I’ve been mulling over. 

### Difference-in-Differences with multiple time periods
- https://www.sciencedirect.com/science/article/abs/pii/S0304407620303948
- https://arxiv.org/abs/1803.09015

Discussion: 
- https://bcallaway11.github.io/did/articles/multi-period-did.html

### Efficient Estimation for Staggered Rollout Designs
- https://arxiv.org/pdf/2102.01291

### The stepped wedge cluster randomised trial: rationale, design, analysis, and reporting
- http://dx.doi.org/10.1136/BMJ.h391

Thoughts: The RCT of staggered DiD. 

### Extensible Experimentation Platform: Effective A/B Test Analysis at Scale
- https://www.researchgate.net/publication/388630852_Extensible_Experimentation_Platform_Effective_AB_Test_Analysis_at_Scale

Idea: A/B testing at scale: 100,000 experiments/year are now run at Microsoft based on a new paper to appear in ICSA 2025.

### Difference-in-Differences Designs: A Practitioner’s Guide
- https://arxiv.org/pdf/2503.13323

### Marketing RCTs etc
- https://arxiv.org/pdf/2201.07055

Thoughts: Interesting paper on varying approaches in marketing. Probably the strength of this paper is the comparison of multiple methods and the “meta-analysis” being done. Their work shows the effect is over estimated by DML and SPSM.

### RieszBoost: Gradient Boosting for Riesz Regression

- https://arxiv.org/pdf/2501.04871

Idea: New paper on estimating treatment function using gradient boosting. Helpful in high dimensional settings. 

### A/B Testing Intuition Busters
- https://drive.google.com/file/d/1oK2HpKKXeQLX6gQeQpfEaCGZtNr2kR76/view

### DiD Resources

- https://psantanna.com/did-resources/

### ProRCA: A Causal Python Package for Root Cause Analysis 
- https://arxiv.org/pdf/2503.01475

Thoughts: Not a fan of Pearlean Causal Inference. We can talk about how the counterfactuals DoCalculus use are not realistic. But aside from that, a great way to begin merging the ideas of RCA and causal.
### Nonparametric causal decomposition of group disparities

- https://projecteuclid.org/journals/annals-of-applied-statistics/volume-19/issue-1/Nonparametric-causal-decomposition-of-group-disparities/10.1214/24-AOAS1990.full

### Causal Factor Analysis is a Necessary Condition for Investment Efficiency

- https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5031574
- https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5131050

### Causal Bayesian Optimization with Unknown Causal Graphs
- https://arxiv.org/pdf/2503.19554

### Why Propensity Scores Should Not Be Used for Matching
- https://gking.harvard.edu/sites/scholar.harvard.edu/files/gking/files/pan1900011_rev.pdf

### DOES REGRESSION PRODUCE REPRESENTATIVE CAUSAL RANKINGS?
- https://apoorvalal.github.io/pdfhosting/pdf/regrank.pdf

### Causal Inference and Uplift Modeling: A review of the literature
- https://proceedings.mlr.press/v67/gutierrez17a/gutierrez17a.pdf

### CATE and ITE Under Ignorability Assumptions
- https://arxiv.org/pdf/2108.04939

### Copula-based Sensitivity Analysis for Multi-Treatment Causal Inference with Unobserved Confounding
- https://arxiv.org/pdf/2102.09412

## Articles

### CausalPy
- https://nathanielf.github.io/talks/pycon_ireland_causalpy/pycon_2024.html#/title-slide
### Tracking outliers in A/B testing
- https://statsig.com/blog/tracking-outliers-ab-testing

### More Power More Underpowered A/B Tests
- https://blog.conductrics.com/cupeds-sting-more-power-more-underpowered-a-b-tests/

### Can causal analysis change business? Applying causality in AI and beyond
- https://nraden.medium.com/part-1-can-causal-analysis-change-business-applying-causality-in-ai-and-beyond-db614aa6eeed

### Machine Learning Regression Adjustments in A/B Tests
- https://yasenov.com/2023/08/machine-learning-regression-adjustments-in-a-b-tests/

### MIT: CausalML
- https://archive.is/2025.03.18-090955/https://sloanreview.mit.edu/article/a-new-machine-learning-approach-answers-what-if-questions/

## Packages/Code

### py why llm
- https://github.com/py-why/pywhyllm

Note: Experimental library integrating LLM capabilities to support causal analyses

### Introduction to Bayesian A/B Testing
- https://github.com/pymc-devs/pymc-examples/blob/main/examples/causal_inference/bayesian_ab_testing_introduction.ipynb
- broken: https://www.pymc.io/projects/examples/causal_inference/bayesian_ab_testing_introduction.html

### CausalLift: Python package for Uplift
- https://causallift.readthedocs.io/en/latest/contents/00.html

### Staggered Rollout Design
- https://github.com/jonathandroth/staggered

### Staggered Design
- https://github.com/bcallaway11/did (R)
- https://github.com/d2cml-ai/csdid (Python) 

### DoubleML package
- https://docs.doubleml.org/stable/index.html

### CausalML Notebooks
- https://github.com/ostojanovic/causalML/tree/main

### Building a Counterfactual Energy Model for Savings Verification
- https://www.reimagine-energy.ai/p/code-tutorial-building-a-counterfactual

### Efficient and sharp policy learning under unobserved confounding
- https://github.com/konstantinhess/Efficient_sharp_policy_learning

### Causal Modeling in Machine Learning Workshop 
- https://github.com/altdeep/causalML?tab=readme-ov-file#causal-modeling-in-machine-learning-workshop-repository

