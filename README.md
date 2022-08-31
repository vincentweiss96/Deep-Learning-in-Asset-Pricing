# Deep-Learning-in-Asset-Pricing
I follow the steps described in Chen, Pelger, &amp; Zhu (https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3350138): Assets are priced with a Stochastic Discount Factor, and test assets are selected using an Adversarial Network.


 
in "Prototype_2":
I define the model
I pull data from a database I created based on large dataset
I put the data into the model and train it

in "Prototype_Eval":
I pull the data again
I make predictions using the model
I compare a Buy-and-Hold strategy against the model strategy

unfortunately the sharpe ratio does not increase, as suggested in the paper I used as a foundation
it was an interesting exercise though
these are just a few extracts from what I have tried to build this model (parameter tuning, training data generation, model specification, etc.)
