# Notes

* MC implies some sort of random sampling, so i take it that the reason importance sampling is an mc method is because it takes samples from the proposal dist, which it is i guess sampling randomly with the purpose of exploring the actually prob dist f(.)

* the sequential part of importance sampling is just that you hav emultiple samples at each observation state that come together after each sample in some big join weight to get the new proposal distribution at each time step, so for one timestep your doing multiple 'threads'


# Questions

* How does the sum of a dirac delta function make a approximation of a target distribution after you sample it? also does it make a continuous funciton or are we using some ort of bayesian inference to make it continous or do we just not care bc we are computing stuff in time steps anyway.

* where is the new sample dist coming from for each sample is it the dirac delta approximation thingy of the target dist, although i thought that importance sampling never actually generated new samples and that was one of the draw backs of it, so is that what the resampling is or something?

* this screenshot doesn't acutally say where if anywhere the posterior dist is being used: should it be used somewhere?


![images](images/Screenshot%20from%202024-10-17%2013-54-06.png)