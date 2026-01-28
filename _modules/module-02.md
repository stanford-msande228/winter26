---
title: Causal Estimation with Machine Learning
---

Jan 20
: **Lecture 8**{: .label .label-green } Flexible Causal Estimation with Machine Learning I: Doubly Robust Learning and Debiasing
    : [[Slides]](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/MSANDE228_Lecture4.pdf)
    : [[Notes]](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/lecture_notes/lecture4_student_notes.pdf)
    : [[NotebookLM]](https://notebooklm.google.com/notebook/b72fc5a1-42cb-4a9c-a66e-f5aeeed72f6e?authuser=1)
: Confidence intervals and asymptotic normality, why naive ML is problematic for confidence intervals of causal quantities, cross-fitting, debiasing, the doubly robust estimator.
: ***Reading Materials***
- [Textbook: Chapter 9](http://www.causalml-book.org)
- Chernozhukov et al. (2018), Double/debiased machine learning for treatment and structural parameters (optional)
- Bang & Robins (2005), Doubly robust estimation in missing data and causal inference (optional)
: ***Coding Materials***
- [g-estimator, g-estimator with crossfitting, DR estimator with crossfitting on Synthetic Example](https://colab.research.google.com/drive/1eTzl2Uiy-ik7hbWnflsNy8hNkK1NdE4M?usp=sharing)

Jan 21
: **Homework**{: .label .label-blue } HW2 Released, Wednesday (Doubly Robust Estimation)


Jan 22
: **Lecture 8**{: .label .label-green } Flexible Causal Estimation with Machine Learning II: ML Predictive Modeling
    : [[Slides]](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/MSANDE228_Lecture5.pdf)
    : [[Notes]](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/lecture_notes/lecture5_student_notes.pdf)
    : [[NotebookLM]](https://notebooklm.google.com/notebook/424a61e6-5b58-487b-bb8f-4880f34ee94b?authuser=1)
: Solving prediction problems with 
ML, cross-validation, AutoML, semi-cross-fitting, stacking.
: ***Reading Materials***
- [Textbook: Chapters 1, 3, 8](http://www.causalml-book.org)
: ***Coding Materials***
- [Overview of ML Methods + AutoML + Stacking](https://colab.research.google.com/drive/14i4_72k3VmjZbHhamW6qGH_uG3sbZo3O?usp=sharing)


Jan 27
: **Lecture 6**{: .label .label-green } Analyzing Experiments with Precision 
    : [[Slides]](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/MSANDE228_Lecture6.pdf)
: Variance of Doubly Robust Estimator, Linear Regression under mis-specification, Linear Regression for RCTs, Precision Improvement
: ***In Class Activity Results***
- [Table of Pros and Cons of each ATE Estimator](https://github.com/stanford-msande228/winter26/raw/main/assets/presentations/lecture_notes/lecture6_activity_notes.pdf)
: ***Reading Materials***
- [Use of Machine Learning to Estimate the Per-Protocol Effect of Low-Dose Aspirin on Pregnancy Outcomes](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2789846)
- [EconML LinearDRLearner](https://www.pywhy.org/EconML/_autosummary/econml.dr.LinearDRLearner.html)
- [DoubleML DR Learner](https://docs.doubleml.org/stable/api/generated/doubleml.irm.DoubleMLIRM.html)
- [Using Causal Inference to Improve the Uber User Experience](https://www.uber.com/blog/causal-inference-at-uber/)

Jan 28
: **Homework**{: .label .label-red } HW2 Due, Wednesday

Jan 28
: **Homework**{: .label .label-blue } HW3 Released, Wednesday (Analyzing Experiments with Precision)

Jan 29
: **Lecture 7**{: .label .label-green } Analyzing Experiments with Precision II
: Inference with High-Dimensional Linear Models, Analyzing Experiments with Precision, FWL & Partialling Out for Low and High-Dimensional Linear Models, Continuous Treatments and Partial Linearity
: ***Reading Materials***
- [Textbook: Chapter 1](http://www.causalml-book.org)
- [Textbook: Chapter 2](http://www.causalml-book.org)
- Angrist & Pischke, Mostly Harmless Econometrics (optional background)
- Lin (2013), Agnostic notes on regression adjustments to experimental data (optional)
: ***Coding Materials***
- [Pennsylvania Re-employment Bonus Experiment (notebook)](https://github.com/CausalAIBook/MetricsMLNotebooks/blob/main/CM1/python-rct-penn-precision-adj.ipynb)
- [Simulated precision via adjustment (notebook)](https://github.com/CausalAIBook/MetricsMLNotebooks/blob/main/CM1/python-sim-precision-adj.ipynb)



Feb 3
: **Homework**{: .label .label-red } HW3 Due, Tuesday

Feb 3
: **Lecture 9**{: .label .label-green } General Debiased Machine Learning Framework
: Partially Linear Models, Continuous Treatments, Generalized FWL theorem, Parameters defined via moment restrictions and the general principle of Neyman orthogonality
: ***Reading Materials***
- [Textbook: Section 9.4](http://www.causalml-book.org)



Feb 3
: **Homework**{: .label .label-blue } HW4 Released, Tuesday (Partially Linear Models)
