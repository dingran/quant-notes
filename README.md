# Quantitative Interview Preparation Guide

### Quantitative interviews 
in finance industry tend to cover a diverse set of topics in math, statistics, computer science and machine learning, and thus can pose some challenges for preparation. After going through the interview process and/or worked in the industry for a while, a few of us decided to put toegther a preparation guide. We come from a technical background (advanced degrees in quantitative field and/or worked in technology industry) and hope this writing will help people with similar background make a successful transition into quantitative finance (if that is what you decided you want to do, of course).

Depending on the types of firm (e.g. buy-side vs sell-side), functional areas (risk modelling, portfolio optimization, trading signal generation etc), the amount of code vs. math involved (e.g. developer vs researcher), the distance to trading and the types of trading (strategy, frequency etc), there are many types of quant jobs and we encourage you to explore and understand the distinctions between them in order to better gauge your interest and fit.

### In this writing
we selected 7 technical areas, they range from "old" math to the industry's new favorate: machine learning. For each area we will have a number of topics. We have intentionally left out finance topics, since we believe we won't be able to do a better job than the existing classic text on them.

We strive to make sure to only include content that is pertinent and deliver it in a concise, intuitive, and self-contained fashion. We will focus on generalizable knowledge points, methods and problem solving strategies rather than exact questions. (For those interested in interview question pool please visit *link_to_other_sites* instead).

This writing will use Jupyter notebooks due to its easy of displaying LaTex equations, code blocks and graphics. One notebook per topic. This README file will keep a list of topics we plan to write about. Once a topic is drafted, the plain text with be replaced with a link pointing to the [nbviewer](https://nbviewer.jupyter.org/) rendering of the notebook.

### Contribute
If you have feedback or wish to contribute to this writing, please do feel free to open an issue or submit a pull request.

--- 
## Table of Content

  * [Calculus](#calculus)
  * [Linear algebra](#linear-algebra)
  * [Probability](#probability)
  * [Statistics](#statistics)
  * [Programming essentials](#programming-essentials)
  * [Numerical methods and optimization](#numerical-methods-and-optimization)
  * [Machine learning](#machine-learning)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc.go)

---

## Calculus
- Derivatives
    - product rule, chain rule, power rule, L'Hospital's rule,
    - partial and total derivative (e.g. z = y*x, y= 2*x)
    - things worth remembering
        - common function's derivatives
        - limits and approximations
    - Applications of derivatives
        - monotonicity, max/min
- Integration
    - power rule, integration by sub, integration by part
    - change of coordinates
- Taylor expansion
    - single and multiple variables
    - Taylor/McLauren series for common functions
    - Derive Newton-Raphson
- ODEs
- PDEs


## Linear algebra
- vector and matrix multiplication
- matrix operations (transpose, determinant, inverse etc)
- types of matrices (symmetric, hermition, orthogonal etc)
- eigenvalue and eigenvectors
- matrix calculus (gradients, hessian etc)
- useful theorems
- matrix decomposition
- applications, types of problems



## Probability
Probability puzzles are reported to be the hardest and most unpredictable type of interview questions. This does not have to be the case for you.
Solving probability interview questions is really all about pattern recognition and then applying the correct tools/theorems.
Once you recognize the underlying mechanics of a problem it is usually no more than two or three quick steps away from the answer.
What this requires is a thorough and, more importantly, intuitive understanding of the key concepts, coupled with sufficient amount of practice to improve your patter recognition skills.

Probability problems should be fun to solve and let's begin!


- [Basic concepts](https://nbviewer.jupyter.org/github/rd1019/quant-interview-tips/blob/master/prob/prob_concepts.ipynb)
    - Event, outcome, random variable, probability and probability distributions

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

- [Approximation method: Central Limit Theorem](https://nbviewer.jupyter.org/github/rd1019/quant-interview-tips/blob/master/prob/central_limit_theorem.ipynb)
    - Definition, examples (unfair coins, Monte Carlo integration)

- [Approximation method: Poisson Paradigm](https://nbviewer.jupyter.org/github/rd1019/quant-interview-tips/blob/master/prob/poisson_paradigm.ipynb)
    - Definition, examples (duplicated draw, near birthday problem)


- Poisson count/time duality
    - poisson from poissons

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

## Machine learning
- Models: See [these blog series](http://dshacker.blogspot.com/2015/07/machine-learning-and-statistics-unified.html) for reference
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




