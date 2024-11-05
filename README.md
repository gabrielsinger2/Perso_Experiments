# Perso_Experiments
In this repo you'll find my computer (Python) experiences, each notebook exploring a theme I've been wondering about in my spare time. 

- Learning ODE: I wanted to compare the ability of (little) neuronal network to learn simple ODE and how efficient they are for generalization. (short notebook)

|![Generalisation time for MLP and ResNet](maximum_generalisation_time_xprime_x_MLP.png)| ![Plot of the 'optimal weights' MLP](MLP_xprime_x.png)| |---|---|

- I took part in the ENS challenge proposed by ELMY, an electricity trading company, involving the supervised modeling of the price differential between the intraday market and the SPOT market. The price differential can be modeled by regression, but also by classification, since what matters above all is to correctly predict the direction of this differential (whether one price will be higher or lower than the other).
I dived into data engeneering, data science in practice and LLM since I used two models (XGBoost) and Prophet LLM time serie forecasting [ProphetTS](https://arxiv.org/abs/2303.01903). I was ranked 71/361.
