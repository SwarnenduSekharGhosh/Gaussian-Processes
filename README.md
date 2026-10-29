# Gaussian-Processes

Probability is used to represent our beliefs about uncertain quantities providing a formal framework to express and manage rational beliefs under uncertainty. Baye's rule offers a systematic approach of updating these beliefs about a given hypothesis as new information becomes available.  This process is known as Bayesian Inference. 
Bayesian inference utilises inductive learning through Bayes rule to update our understanding and make informed decisions. 

P(H|E) = P(E|H)*P(H)/P(E)

A "conjugate prior" refers to a prior distribution which when combined with a specific likelihood function results in a posterior distribution that belongs to the same family of distribution as the prior. This property simplifies the process of updating the belief when new data becomes available as the posterior distribution can be calculated easily. The conjugate prior relationship helps in obtaining easy analytical solution for the posterior. Instead of performing full marginal integration, the posterior can be directly computed by updating the parameters of the prior based on the observed data.

One such conjugate prior distribution is the "Gaussian distribution". While dealing with a normally distributed data with a Gaussian likelihood assumption,  choosing a Gaussian prior to the mean parameter results in a posterior distribution which is also Gaussian.
