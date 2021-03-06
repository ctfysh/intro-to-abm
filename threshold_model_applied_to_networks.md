# Threshold Model Applied to Networks
People may not make the decision to contribute to the public good based on the contribution rate of society at large, but rather based on whether their friends contribute. Therefore we look at a network perspective of collective action and implement the same threshold logic as above to agents on the network.

We will use a small world network and explore the consequences of different rewiring probabilities. Each agent has a threshold and each tick agents will check whether the share of participation among their friends is above their threshold. If so, they will adopt to contribute to the collective action problem.

At the start of the simulation one of the agents is picked at random to contribute. Figure 6 shows an example of a diffusion of collective action. When all agents were in one population we had, over 1000 runs, an average group size of 1.3 for the Gaussian distribution and 22.8 for the uniform distribution. In a networked environment the Gaussian distribution of thresholds lead to an average group size of 2.5 and 4 for the uniform distribution. It is unlikely to have collective action spread through the whole population since diffusion of cooperative behavior is easily blocked by a few agents who do not want to collaborate, e.g., having a high threshold.

![](https://raw.githubusercontent.com/comses/intro-to-abm/master/assets/images/Ch_15_Fig_6.png)<br>*
Figure 6. Screenshot of diffusion of collective action in a small world network.*

[NETLOGO EXAMPLE: THRESHOLD IN NETWORKS IN](https://raw.githubusercontent.com/comses/intro-to-abm/master/assets/netlogo/thresholdnetworks.nlogo)<br>*Model: Right click on the Link and Save it. Open Netlogo and Run it with NetLogo.*
