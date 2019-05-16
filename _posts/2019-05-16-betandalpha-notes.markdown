---
layout: post
title:  "Notes on betandalpha"
date:   2019-05-16 10:17:50 +0200
categories: jekyll update
---

As a preparation for the course we plan to read:
1. [Probability Theory (For Scientists and Engineers)](https://betanalpha.github.io/assets/case_studies/probability_theory.html)
2. [Conditional Probability Theory (For Scientists and Engineers)](https://betanalpha.github.io/assets/case_studies/conditional_probability_theory.html)
3. [Probabilistic Modeling and Statistical Inference](https://betanalpha.github.io/assets/case_studies/modeling_and_inference.html)
4. [Towards A Principled Bayesian Workflow](https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html)

# Terms

## When Riemann Integral is not enough.

Motivations for a new integral (Lebesgue Integral) or problems with the Riemann integral.
1. Computing Riemann integral in high dimensional domains could be very labourious.
2. Ww cannot integrate if we have a function with an uncountably infinite number of discontinouities.
3. Intergenching limits and integral signs requires uniform convergence (a very strong condition).

["Many important functions did not have a Riemann integral and the theory lacked strong convergence theorems for taking the integral of the limit of a sequence of functions.
Swapping limit and integral would require uniform convergence, a rather heavy and restrictive requisite."]

Infinitely many discontinuity points CAN destroy the Riemann integrability. For example, all monotonically increasing functions are Riemann integrable. However, having measure zero for this set of discontinuities is not sufficient since the function has also to be bounded.

Riemann Integrals can still work with uncountable infinite descontinouities as long the set of discontinuities has measure zero and the function is bounded.

# Questions
A little quiz

- What is the Weldorf accumulator?
Is a method that accurately computes the empirical mean and variance of a sample in a single pass.
- What is the Monte Carlo method?
- What is Markov Chain Monte Carlo?

What is Probabilistic reasoning?
Probabilistic reasoning allows us to reason about the outcomes of random experiments, given the preceding mathematical structure. 
Given P(X) say something about the data.

What is statistical learning?
Statistical learning, on the other hand, essentially deals with the inverse problem: We are given the outcomes of experiments, and from this we want to infer properties of the underlying mathematical structure. Given data X say sometyhing about P(X)

What is a data generating process?
[from quora](https://www.quora.com/How-is-the-data-generating-process-DGP-different-from-the-model-in-regression-analysis)

Why the model is (usually) not perfect:
- simplifying assumptions
- incomplete information
- measurements have errors
- the data generating process can change trhough time

