---
title: Research
type: landing

sections:
  - block: features2
    content:
      title: "Research"
      items:
        - name: "Job Market Paper"
        - name: "Inference for Missing Data with State-Space Models"
          description: "
          *with Gregor Reich*
          <br>
          <br>
          Nonlinear, non-Gaussian state-space models are a standard tool for analyzing time series or panel data with latent state variables, but estimating their parameters and, even more so, the latent states is challenging. We provide a comprehensive methodology to estimate the latent states, particularly addressing two issues: First, because the latent state is serially correlated, accurate point estimators and prediction bands require evaluating high-dimensional integrals arising from marginalizing the latent path. We propose a deterministic recursive quadrature and interpolation (RQI) algorithm to approximate these integrals, exploiting the efficiency of lower-dimensional numerical algorithms. Second, ignoring uncertainty about the model parametrization yields overconfident prediction bands. We develop a framework of prediction-band unions that incorporate parameter uncertainty, which can be computed via a sequence of constrained optimization problems solvable with off-the-shelf packages. We demonstrate the efficiency of RQI in extensive Monte Carlo studies for a Stochastic Volatility model, benchmarking against RQI a popular particle smoothing algorithm. Finally, we conduct full predictive inference for a sequence of endogenously unobserved prices using data from a steel-trading firm and a dynamic profit-maximization model.
          <br>
          <br>
          [**PDF**](/uploads/JMP_Gilch.pdf)"
        - name: ""
          description: "![image](/uploads/PU-vs-plugin-band-T20-nox0.png)"
        - name: "Publications"
        - name: "Small Data: Inference with Occasionally Observed States"
          description: "
          *with Andreas Lanz, Philipp Müller, Gregor Reich, and Ole Wilms*
          <br>
          **Accepted at Management Science**
          <br>
          <br>
          We study the estimation of dynamic economic models for which some of the state variables are observed only occasionally by the econometrician---a common problem in many fields, ranging from marketing to finance to industrial organization. If those occasional state observations are serially correlated, the likelihood function of the model becomes a high-dimensional integral over a nonstandard domain. We generalize the recursive likelihood function integration procedure (RLI; Reich, 2018) to incorporate the occasional observations, enabling likelihood-based inference in such estimation problems. In extensive Monte Carlo studies, we demonstrate the favorable properties of the proposed method for identifying all model parameters and compare it to alternative methods.
          <br>
          <br>
          [**DOI**](https://pubsonline.informs.org/doi/full/10.1287/mnsc.2022.00246) · [**PDF**](/uploads/Gilch-etal-2025-SmallData.pdf)"
        - name: ""
          description: "![image](/uploads/lrr_kernels_rho-eps-converted-to-1.jpg)"
        - name: 
        - name: "Sparse tensor product approximation for a class of GMM estimators"
          description: "
          *with Michael Griebel and Jens Oettershagen*
          <br>
          **International Journal for Uncertainty Quantification, 2022**
          <br>
          <br>
          Generalized Method of Moments (GMM) estimators in their various forms, including the popular Maximum Likelihood (ML) estimator, are frequently applied for the evaluation of complex econometric models with not analytically computable moment or likelihood functions. As the objective functions of GMM- and ML-estimators themselves constitute the approximation of an integral, more precisely of the expected value over the real world data space, the question arises whether the approximation of the moment function and the simulation of the entire objective function can be combined.

          Motivated by the popular Probit and Mixed Logit models, we consider double integrals with a linking function which stems from the considered estimator, e.g. the logarithm for Maximum Likelihood, and apply a sparse tensor product quadrature to reduce the computational effort for the approximation of the combined integral. Given Hölder continuity of the linking function, we prove that this approach can improve the order of the convergence rate of the classical GMM- and ML-estimator by a factor of two, even for integrands of low regularity or high dimensionality. This result is illustrated by numerical simulations of Mixed Logit and Multinomial Probit integrals which are estimated by ML- and GMM-estimators, respectively.
          <br>
          <br>
          [**DOI**](https://www.doi.org/10.1615/Int.J.UncertaintyQuantification.2021037549) · [**PDF**](/uploads/GilchGriebel-2021-SparseProductApprox.pdf)"
        - name: ""
          description: "![image](/uploads/quad-gmm-convergence.jpg)"
        - name: "Working Papers"
        - name: "Financial Sanctions Interact(ed) with Trade Sanctions"
          description: "
          *with Christian Bayer and Farzad Saidi*
          <br>
          <br>
          Trade and financial sanctions have played and continue to play a prominent role in geopolitics. We show empirically that there is a strong nonlinearity in their interaction. While both types of sanctions can significantly harm the sanctioned country in terms of GDP losses, their combined effect exceeds the sum of its parts. When financial sanctions precede trade sanctions, they amplify the effect of the latter, but not vice versa. We theoretically argue that this finding is related to the fact that financial sanctions weaken the financial sector of the sanctioned country and, thus, also amplify all other shocks, while trade sanctions are mainly an impulse. As a result, if a trade sanction is imposed after a financial sanction, the aggregate business cycle effects are exacerbated; but if a trade sanction precedes a financial sanction, it is not amplified further
          <br>
          <br>
          [**PDF**](/uploads/BayerGilchSaidi-2025-Sanctions.pdf)"
        - name: ""
          description: "![image](/uploads/event-study-finb4trade.png)"
        - name: "Work in progress"
        - name: "Asymptotic Properties of the Maximum Likelihood Estimator under Occasionally Observed States"
          description: "
          *with Gregor Reich and Ole Wilms*
          <br>
          <br>
          Estimating Markov models with hidden state variables presents significant challenges because the likelihood involves a high-dimensional integral over the unobserved states. This complication renders the standard approach to prove the asymptotic properties of the likelihood-based estimator infeasible, because it relies on a log-transformation of the likelihood function. Moreover, the need to numerically approximate the integral in the likelihood function introduces an additional source of error in the estimation process. In this paper, we demonstrate how occasional observations of the hidden state restore the feasibility of the log-likelihood approach or establishing asymptotic properties, thereby extending existing results to general state spaces for the hidden state. Further, we show that, given consistency and asymptotic normality of the exact estimator, the desired properties can be extended to the estimator based on the approximated likelihood.
          <br>
          <br>
          [**PDF**](/uploads/Gilch-etal-2025-AsympOccObs.pdf)"
        - name: ""
          description: "![image](/uploads/eq-asymp-occ-obs.jpg)"
---