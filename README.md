# Quantitative Finance Interview Questions and Strategies

## Introduction

### Purpose
The purpose of this writing is to provide a "in-a-nutshell" kind of summary on key topics frequently tested in quantitative interviews in finance.
The most relevant roles are quantitative researchers/developers/analysts, portfolio researcher/analysts, risk modeller/analysts etc.
More recently, we also saw tech-heavy data scientist/machine learning scientist interviews to start feature similar types of questions discussed here.

### Who are we
The lead contributors so far (we hope to see more contributors as this project evolves) typically have an advanced degree in a
quantitative field (some of them also spent time at top tech firms) and then made a successful transition into finance (top hedge funds and banks).

### Writing guidelines
We strive to make sure to only include content that are pertinent and deliver it in a concise, intuitive, and self-contained fashion.
We will focus on generalizable knowledge points, methods and problem solving strategies rather than exact questions.
(For those interested in interview question pool please visit *link_to_other_sites* instead)


## Table of Content
---

  * [Calculus](#calculus)
  * [Linear algebra](#linear-algebra)
  * [Probability](#probability)
  * [Statistics](#statistics)
  * [Programming essentials](#programming-essentials)
  * [Numerical methods and optimization](#numerical-methods-and-optimization)
  * [Machine learning concepts](#machine-learning-concepts)
  * [Contribute](#contribute)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

---

## Calculus


## Linear algebra
- vector and matrix multiplication
- matrix operations (transpose, determinant, inverse etc)
- types of matrices (symmetric, hermition, orthogonal etc)
- eigenvalue and eigenvectors
- matrix calculus (gradients, hessian etc
- useful theorems



## Probability
Probability puzzles are reported to be the hardest and most unpredictable type of interview questions. This does not have to be the case for you.
Solving probability interview questions is really all about pattern recognition and then applying the correct tools/theorems.
Once you recognize the underlying mechanics of a problem it is usually no more than two or three quick steps away from the answer.
What this requires is a thorough and, more importantly, intuitive understanding of the key concepts, coupled with sufficient amount of practice to improve your patter recognition skills.

Probability problems should be fun to solve and let's begin!


- Event, outcome, random variable, and probability

- Combinatorics
    - Permutation
    - Combinations
    - Inclusion-exclusion

- Conditional probability
    - Bayes rule
    - Law of total probability
 
- Probability Distributions
    - Expectation and variance equations
    - Discrete probability and stories
    - Continuous probability: uniform, gaussian, poisson

- Expectations, variance, and covariance
    - linearity of expectation
        - solving problems with this theorem and symmetry
    - law of total expectation
    - covariance and correlation
    - independence implies zero correlation
    - hash collision probability

- Universality of Uniform distribution
    - proof
    - circle problem

- Order statistics
    - expectation of min and max and random variable

- Graph-based solutions involving multiple random variables
    - breaking stick
    - meeting at the train station
    - simplex
    - frog jump

- Approximation trick1: [Central limit theorem](prob_clt.ipynb)
    - fake coin
    - monte carlo integration

- Approximation trick2: Poisson paradigm
    - birthday problem, birthday triplets, near birthday problem
    - repeated draws

- Poisson count/time duality
    - possion from possions

- Markov chain tricks
    - various games
    - introduction of martingale


## Statistics
- z score, t-test, F-test, chi2 test
- p-value
- sampling
- AIC, BIC


## Programming essentials
The bare minimum of coding concept you need to know well.

Material on these topics are widely available elsewhere, so we will just cite them here.

- Data structures:
    - array, dict, link list, tree, heap, graph, ways of representing sparse matrix

- Sorting:
    - brilliant.org

- Tree/Graph related algorithms
    - traversal (BFS, DFS)
    - shortest path (two sided BFS, djikstra)
- Recuision, iteration and DP

## Numerical methods and optimization
- computer errors (e.g. float)
- root finding (newton method, bisection, secant etc)
- interpolating
- numerical integration and difference
- finite difference
- numerical method in linear algebra
    - solving linear equations
    - matrix decompositions
    - eigen problems
    - special cases

## Machine learning concepts
- Models
    - linear regression
    - logistic regression
    - tree methods
    - SVM
    - generative vs descriptive models
        - Gaussian mixture, Naive bayes
- Learning theory
    - bias vs variance
    - feature selection
    - model validation
    - model metrics
    - ensemble method, boosting, bagging
- Deep learning topics



## Contribute
If you wish to contribute to this writing, feel free to submit a PR.

If you wish to contribute anonymously, please contact us at TBD
