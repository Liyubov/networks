
# Random walk analysis

Random walk is a key concept for many fields of natural science. 
Here we consider several types of random walks: 
1. simple markovian random walks without memory: $X_{n+1} = X_{n} + \epsilon_n$, where $\epsilon_n$ is not step-dependent;
2. non-markovian random walks with memory, including self-repelling random walks: $X_{n+1} = X_{n} + \epsilon_n(X_{n-1}, ..., X_{n-k}).$ This model was used for modelling of polymer chains.


To learn more about the basic random walk theory you can visit

https://en.wikipedia.org/wiki/Random_walk 


# Code for random walks analysis

First, in jupiter notebook *random_walks.ipynb* we analyze standard random walks analysis in 1D. 

Then I do simulations for continuous time random walk model (CTRW) in 2D, but this can be extended to 3D and when the underlying structure is discrete, e.g. network or if underlying surface has more complex heterogeneous topology.

In *analysis_of_trajectories.ipynb* I analyse the random walk trajectories from data or from randomly generated trajectories.


# References and literature materials

There is one classical book about random walks https://global.oup.com/academic/product/first-steps-in-random-walks-9780199234868?cc=fr&lang=en&

This project is based on the model described in our recent articles:
1. L.Tupikina, D.Grebenkov “Temporal and structural heterogeneities in networks” Applied network Journ. (2019)
2. D.Grebenkov, L. Tupikina “Heterogeneous continuous time random walk”, link to Physical Rev. E Journal  E 97, 012148 (2018)

The research questions are description of the continuous limits of CTRW (random walk in continuous time on networks), 
Ito-Stratonovich dilemma. Research project with Ecole Polytechnqiue, CRI 
https://sites.google.com/view/fellowshipresultsliubov/research-projects/anomalous-diffusion-analysis?authuser=0

For more details and for example of datasets you can look at 
http://inadilic.fr/data/ 
