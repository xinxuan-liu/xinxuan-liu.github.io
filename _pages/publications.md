---
layout: page
permalink: /research/
title: research
description:
nav: true
nav_order: 2
---

#### Job Market Paper

**Beyond the Average and the Observed: Distributional Tests of Treatment Effect Heterogeneity in Regression Discontinuity Designs**

Existing tests look for heterogeneous treatment effects by splitting the sample along covariates chosen in advance. This paper tests for heterogeneity anywhere in the outcome distribution, with no covariates specified, so it detects effects that vary with unobservables. Applied to the effect of Islamic municipal rule on female education in Turkey.

<details>
<summary>Abstract</summary>
<p>This paper proposes distributional tests of treatment effect heterogeneity in regression discontinuity designs. While existing tests compare average effects across subgroups defined by observed covariates, our tests instead detect heterogeneity anywhere in the outcome distribution and require no choice of covariates, so they also capture heterogeneity driven by unobservables. The tests ask whether the treated outcome distribution at the cutoff is a constant shift of the control distribution. We compare the two distributions after aligning them by the estimated shift and obtain critical values by permutation inference. When the shift is known, the permutation test is exact in finite samples; when it must be estimated, a Durbin problem arises and the test is no longer valid. We provide two remedies: a Khmaladze martingale transformation that removes the drift induced by estimation, and a prepivoted permutation test that reproduces that drift in the reference distribution. Both are asymptotically valid. In Monte Carlo simulations, the two tests hold their nominal size not only in large samples but also in small ones, and they have power against latent heterogeneity. We apply the tests to the effect of Islamic municipal rule on female education in Turkey and find evidence of heterogeneity within more religious municipalities that a comparison of average effects would miss.</p>
</details>

[PDF](/assets/pdf/Xinxuan_Liu_JMP.pdf)

---

#### Working Papers

**Learning from Déjà Vu: Contextual Bandit-Based Model Selection for Macroeconomic Nowcasting**

Selects among nowcasting models by finding the past periods whose financial and news conditions most resemble the present and choosing the model that nowcast them best. In real-time US GDP nowcasting from 2006 to 2025, it improves on every benchmark feasible in real time, with the gains concentrated in the pandemic quarters.

**Nowcasting Inflation with a Covariate Foundation Model**

Nowcasts inflation with a pretrained transformer that reads high-frequency energy prices as exogenous inputs. It outperforms the classical mixed-frequency benchmarks on both point and density metrics, and with the month only partly observed it already surpasses every benchmark's full-month accuracy.
