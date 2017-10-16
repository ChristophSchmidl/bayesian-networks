# Bayesian Networks

This repository contains all assignments for the course "Bayesian Networks" (NWI-IMC012) given at the Radboud University.


## Lecture 1 - Introduction to Bayesian Networks

### Learning Objectives

* Know what a Bayesian network looks like
* Understand what a Bayesian network represents

### Lecture Outline

* Optimal Bayes
* Naive Bayes
* Bayesian Networks	

### Notes

* This course should rather be called "**Probabilistic graphical models** (PGMs)" because Bayesian networks is just a subset of the topics covered in the course
* There are different kinds of PGMs:
	* Directed PGMs, also known as Bayesian networks
	* Gaussian PGMs
	* Undirected PGMs
	* PGMs with **latent variables** (from Latin: present participle of lateo (“lie hidden”), as opposed to observable/indicator variables. Also called hidden, conceptual or hypothetical variables. see: http://www.theanalysisfactor.com/what-is-a-latent-variable/)
* Examples of latent variables: Healthiness, Democratic rule, Intelligence.
* How does a directed PGM (Bayesian Network) represents a **joint probability distribution**?
* **Confounding factors* ("Störfaktor") also called confounder, confounding variable or third variable is a variable that influences both the dependent variable and independent variable causing a spurious association. Confounding is a causal concept, and as such, cannot be described in terms of correlations or associations (see: https://en.wikipedia.org/wiki/Confounding and https://explorable.com/confounding-variables)
* Once built, PGMS can be used for many purposes like:
	* **Classification**, e.g. for diagnosis
	* **Prediction**, e.g. the result of an operation
	* **Planning**, e.g. an optimal schedule
	* **Reasoning**, e.g. answering "what-if" queries
*	





## Lecture 2 - Conditional Independence and d-Separation

### Learning Objectives

* Understand the concept of conditional independence
* Understand and be able to apply the d-separation criterion
* Be able to test Bayesian network structure against data

### Lecture Outline

* Conditional Independence
* d-Separation
* Testing conditional independence



## Lecture 3 - Managing Network Complexity

### Learning Objectives

* Understand how Bayesian networks represent data-generating processes
* Keep Bayesian networks manageable
* Be able to interpret and fit parametric Bayesian networks

### Lecture Outline

* Recap: Interpretation of Bayesian Networks
* Manageable Networks: Tricks of the Trade
* Parametric Representations



## Lecture 4 - Structural Equation Models

### Learning Objectives

* Understand the relationships between Bayesian networks and (a subset of) Structural Equation Models (SEMs)
* Apply Bayesian network methodology to SEMs, including model testing

### Lecture Outline

* Gaussian Distributions
* Structural Equation Models (SEMs)
* Testing SEMs



## Lecture 5 - Latent Variables

### Learning Objectives

* Be able to derive implied covariance matrices from SEMs
* Understand the concept of global model fit
* Get acquainted with latent variables in SEM

### Lecture Outline

* Latent Variables
* Implied Covariance Matrices
* Estimating Latent Variables
* Examples



## Lecture 6 - Exact Inference

### Learning Objectives

* Understand why exact inference in Bayesian networks is a hard problem
* Know what factor graphs are and how to derive them from Bayesian networks
* Be able to apply the message passing algorithm to factor graphs

### Lecture Outline

* Exact Inference is NP-hard
* Elimination Orderings



## Lecture 7 - Approximate Inference

### Learning Objectives

* Know what factor graphs are and how to derive them from Bayesian networks
* Be able to apply the message passing algorithm to factor graphs

### Lecture Outline

* Factor Graphs
* Message Passing on Factor Graphs
* Loopy Message Passing



## Lecture 8 - Markov Equivalence and Structure Learning

### Learning Objectives

* Recognize when two Bayesian networks are statistically equivalent
* Understand the concept of "faithfulness" to a probability distribution
* Learn about an algorithm that infers Bayesian network structure from data

### Lecture Outline

* Faithfulness
* Markov Equivalence
* The IC Algorithm



## Lecture 9 - Structure Learning Algorithms

### Learning Objectives

* Understand the principles and limitations of conditional independence testing for continuous data
* Apply structure learning ideas in practice
* Efficiently implement the IC algorithm

### Lecture Outline

* Testing Conditional Independence
* The PC Algorithm



## Lecture 10 - Non-DAG Models

### Learning Objectives

* Understand the limitations that come with using DAGs to represent Bayesian networks
* Know what unidirected graphical models (UGs) and maximal ancestral graphs (MAGs) are
* Understand (superficially) how inference and structure learning work for UGs and MAGs

### Lecture Outline

* Limitations of DAGs
* Ancestral Graphs
* Unidirected Graphical Models



## Lecture 11 - Causality and Intervention

### Learning Objectives

* Understand the difference between correlation and causation
* Appreciate how this complicates empirical research
* Be familiar with the do-operator to define causal effects
* Understand how Bayesian networks help to infer causation

### Lecture Outline

* Motivation
* Covariate Adjustment
* Instrumental Variables

