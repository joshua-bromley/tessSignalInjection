# MCMC Sampler
This folder contains files relating to using an mcmc sampler to determine the shape of an occulter from the light curve

## model.ipynb
This notebook contains the proposed model for the mcmc sampling and is used for testing purposed

## logProbability.ipynb
This notebook contains code to visualize how the log probability changes with different parameters of the model. This notebook is used to see if a variable is a good paramter of the model: if it can be optimized and won't be dominated by other parameters
  
 ## simpleSampler.ipynb
 This notebook contains a Metropolitan-Hastings MCMC sampler written from scratch. It is instructive to see how mcmc sampling works and to see how the different variable change during sampling. It is also useful to help debug the model during sampling. This norebook is also connected to Weights & Biases so runs of this sampler will show up there
 
 ## emceeSampler.ipynb
 This notebook contains a MCMC sampler implementing the emcee package. It is more capable than the simple sampler and should be used to get better results. However, it is not as transparent so if there is an issue with the model, it will probably be easier to solve using the simple sampler
