# Naive-Bayes-Classifier_diabetes_prediction

### 📌 What is Naive Bayes?

The Naive Bayes classifier is a probabilistic machine learning algorithm based on Bayes’ Theorem, used for classification tasks. 

It's called "naive" because it assumes that all features are independent of each other given the class label — an assumption that 

often doesn't hold in real data, but still works surprisingly well in practice.

### 📘 Bayes' Theorem

Bayes’ Theorem describes the probability of a class 𝐶 given a set of features X = ( x1 , x2 ,..., xn ):

                                            P(C∣X) = P(X∣C) ⋅ P(C) / P(X

                  Where:

                      P(C∣X): Posterior probability (probability of class given features)

                      P(X∣C): Likelihood (probability of features given class)
                      
                      P(C): Prior probability of the class

                      P(X): Evidence (probability of features, constant across classes)

### 🧩 Naive Assumption

The classifier assumes feature independence, which simplifies computation:

                                     P(X∣C) = P(x1∣C) ⋅ P(x2∣C)⋅…⋅ P(xn∣C)

This allows efficient estimation of the probabilities using training data.


### 📊 Types of Naive Bayes

| Type               | Suitable For            | Assumption                          |
| ------------------ | ----------------------- | ----------------------------------- |
| **Gaussian NB**    | Continuous data         | Features follow normal distribution |
| **Multinomial NB** | Count data (e.g., text) | Features are counts or frequencies  |
| **Bernoulli NB**   | Binary features         | Features are 0/1 or True/False      |


### ✅ Advantages

Simple and easy to implement

Fast for both training and prediction

Works well with high-dimensional data (e.g., text)

Requires small amount of data to train

### ❌ Disadvantages

Assumes independence among features (often unrealistic)

Struggles when features are correlated

Can be biased if one class dominates



​



