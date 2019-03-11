#### 1 Introduction 1
- 1.1 Machine Learning: what and why?
  - 1.1.1 Types of machine learningp2
- 1.2 Supervised learning 3
  - 1.2.1 Classification p3
  - 1.2.2 Regression p8
- 1.3 Unsupervised learning p9
  - 1.3.1 Discovering clusters p10
  - 1.3.2 Discovering latent factors p11
  - 1.3.3 Discovering graph structure p13
  - 1.3.4 Matrix completion p14
1.4 Some basic concepts in machine learning p16
  - 1.4.1 Parametric vs non-parametric models p16
  - 1.4.2 A simple non-parametric classifier: K-nearest neighbors p16
  - 1.4.3 The curse of dimensionality p18
  - 1.4.4 Parametric models for classification and regression p19
  - 1.4.5 Linear regression p19
  - 1.4.6 Logistic regression p21
  - 1.4.7 Overfitting p22
  - 1.4.8 Model selection p22
  - 1.4.9 No free lunch theorem 

#### 2 Probability 27
- 2.1 Introduction p27
- 2.2 A brief review of probability theory p28
  - 2.2.1 Discrete random variables p28
  - 2.2.2 Fundamental rules p29
  - 2.2.3 Bayes' rule p29
  - 2.2.4 Independence and conditional independence p31
  - 2.2.5 Continuous random variables p32
  - 2.2.6 Quantiles p33
  - 2.2.7 Mean and variance p33
- 2.3 Some common continuous distributions p34
  - 2.3.1 The binomial and Bernoulli distributions p34
  - 2.3.2 The multinomial and multinoulli distributions p35
  - 2.3.3 The Poisson distribution p37
  - 2.3.4 The empirical distribution p37
- 2.4 Some common continuous distributions p38
  - 2.4.1 Gaussian (normal) distribution p38
  - 2.4.2 Degenerate pdf p39
  - 2.4.3 The student's t distribution p39
  - 2.4.4 The Laplace distribution p41
  - 2.4.5 The gamma distribution p41
  - 2.4.6 The beta distribution p43
  - 2.4.7 Pareto distribution p43
- 2.5 Joint probability distributions p44
  - 2.5.1 Covariance and correlation p45
  - 2.5.2 The multivariate Gaussian p46
  - 2.5.3 Multivariate student t distribution p47
  - 2.5.4 Dirichlet distribution p49
- 2.6 Transformation of random variables p49
  - 2.6.1 Linear transformations p49
  - 2.6.2 General transformatioins p50
  - 2.6.3 Central limit theorem p52
- 2.7 Monte Carlo approximation p53
  - 2.7.1 Example: change of variables, the MC way p53
  - 2.7.2 Example pi by Monte Carlo integration p54
  - 2.7.3 Accuracy of Monte Carlo approximation p54
- 2.8 Information theory p56
  - 2.8.1 Entropy p57
  - 2.8.2 KL divergence p589
  - 2.8.3 Mutual information p59

#### Generative models for discrete data p67
- 3.1 Introduction p67
- 3.2 Bayesian concept learning p67
  - 3.2.1 Likelihood p69
  - 3.2.2 Prior p69
  - 3.2.3 Posterior p70
  - 3.2.4 Posterior predictive distributioin p73
  - 3.2.5 A more complex prior p74
- 3.3 The beta-binomial model p74
  - 3.3.1 Likelihood p75
  - 3.3.2 Prior p76
  - 3.3.3 Posterior p77
  - 3.3.4 Posterior predictive distribution p79
- 3.4 The Dirichlet-multinomial model p80
  - 3.4.1 Likelihood p81
  - 3.4.2 Prior p81
  - 3.4.3 Posterior p81
  - 3.4.4 Posterior predictive p83
- 3.5 Naive Bayes classifiers p84
  - 3.5.1 Model fitting p85
  - 3.5.2 Using the model for prediction p87
  - 3.5.3 The log-sum-exp trick p88
  - 3.5.4 Feature selection using mutual information p89
  - 3.5.5 Classifying documents using bag of words p90


#### 3 Generative Models for Discrete Data 67

#### 4 Gaussian Models p99
- 4.1 Introduction p99
- 4.2 Guassian discriminant analysis p103
- 4.3 Inference in jointly Gaussian distributions p112
- 4.4 Linear Gaussian systems p121
- 4.5 *Digression: The Wishart distribution p128
- 4.6 Inferring the parameters of an MVN p129

#### 5 Bayesian Statistics 151
- 5.1 Introduction p151
- 5.2 Summarizing posterior distributions p151
- 5.3 Bayesian model selection p157
- 5.4 Priors p167
- 5.5 Hierarchical Bayes p174
- 5.6 Emperical Bayes p174
- 5.7 Bayesian decision theory p178

#### 6 Frequentitist Statistics p193
- 6.1 Introduction p193
- 6.2 Sampling distribution of an estimator p193
- 6.3 Frequentist decision theory p197
- 6.4 Desirable properties of estimators p202
- 6.5 Emperical risk minimization p207
- 6.6 *Pathologies of frequentist statistics p214

#### 7 Linear Regression p219
- 7.1 Introduction p219
- 7.2 Model specification p219
- 7.3 Maximum likelihood estimation (least squares) p219
- 7.4 *Robust linear regression p225
- 7.5 Ridge regression p227
- 7.6 Bayesian linear regression p233

#### 8 Logistic Regression p247
- 8.1 Introduction p247
- 8.2 Model specification p247
- 8.3 Model fitting p248
- 8.4 Bayesian logistic regression p257
- 8.5 Online learning and stochastic optimization p264
- 8.6 Generative vs discriminitive classifiers p270

#### 9 Generalized Linear models and the exponential family p283
- 9.1 Introduction 
- 9.2 The Exponential family p283
- 9.3 Generalized linear models (GLM) p292
- 9.4 Probit regression p295
- 9.5 Multi-task learning p298
- 9.6 *Generalized linear mixed models p300
- 9.7 *Learning to rank p302


#### 10 Directed Graphical Models (Bayes nets) p309
- 10.1 Introduction p309
- 10.2 Examples p313
- 10.3 Inference p321
- 10.4 Learning p322
- 10.5 Conditional independence properties of DGMs p326
- 10.6 *Influence (decision) diagrams p330