# Bayesian Networks - Exam Preparation


## Lectures


**11 Lectures and 2 tutorials in total**

Lecture topics:

* General Introduction
	* Bayesian Artificial Intelligence by Kevin B. Korb and Ann E. Nicholson. **Chapters 1 and 2**
* Conditional Independence
* Managing Network Complexity
* (Tutorial 1)
* Exact Inference
* Approximate Inference
	* Factor graphs and the sum-product algorithm by F. R. Kschischang, B. J. Frey, H. -A. Loeliger. IEEE Transactions on Information Theory 47(2):498–519,
2001.
* Structural Equation Models
* Latent Variables
* Markov Equivalence
* Structure Learning
* (Tutorial 2)
* Causality I
* Causality II	





## Mock Exam

**100 points in total**

Question topics:

* Bayesian networks basics (14 points)
* Binary Bayesian Networks (28 points)
* Inference (9 points)
* Markov Equivalence (9 points)
* Structure Learning (18 points)
* Causality (12 points)
* Constraints with unobserved variables (10 points)




### Question 1 - Bayesian networks basics (14 points)

* What does **DAG** stand for?
* Factorization of a probability density
* Kinship terminology
	* **Parent**
	* **Child**
	* **Descendant**
	* **Ancestor**
* Terms in a factorization. How does it change when...
* Smallest general upper bound number of parameters for encoding a corresponding probability density factorization
* Based on a graphical representation of a bayesian network, list all variables that match the description
	* Children of X
	* Ancestors of Y




### Question 2 - Binary Bayesian Networks (28 points)

* Given a Bayesian Network of binary variables, how many parameters are needed to represent it using **conditional probability tables**?
* How does the number of parameters change if variables become ternary instead of binary?
* Listing different **d-separation** statements implied by a Bayesian Network
* **Joint probability density** table
* Drawing a Bayesian Network from a joint probability density table
* Complete certain columns in a probability table to that it does not constradict consistency with a certain d-separation statement
* Applying the **divorcing technique** in order to reduce parameters
* Scenarios when the **binning technique** could be applied in order to reduce the number of parameters




### Question 3 - Inference (9 points)

* When is a Bayesian Network a **Polytree**?
* Draw a **factor graph**





### Question 4 - Markov Equivalence (9 points)

* Given a Bayesian network, draw different alternative that are **Markov equivalent**
* Draw a Bayesian network with 4 variables whose **Markov equivalence class** contains only the network itself




### Question 5 - Structure Learning (18 points)

* When is a graph not **faithful** to a certain probability density
* Given a list of **conditional independencies**, perform the **IC** or **PC** algorithm



### Question 6 - Causality (12 points)

* Given a Bayesian Network and its corresponding **joint distribution** determine/calculate
	* p(Y = 1 | X = 1)
	* p(Y = 1 | do(X = 1))
	* sum_z p(Y = 1 | X = 1, z)p(z)




### Question 7 - Constraints with unobserved variables (10 points)

* **Unobserved variables**







