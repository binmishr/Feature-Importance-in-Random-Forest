# Feature-Importance-in-Random-Forest

The Turkish president thinks that high interest rates cause inflation, contrary to the traditional economic approach. For this reason, he dismissed two central bank chiefs within a year. And yes, unfortunately, the central bank officials have limited independence doing their job in Turkey contrary to the rest of the world.

In order to check that we have to model inflation rates with some variables. The most common view of the economic authorities is that the variables affecting the rates are currency exchange rates, and CDS(credit default swap). Of course, we will also add the funding rates variable, the president mentioned, to the model to compare with the other explanatory variables.

Because the variables can be highly correlated with each other, we will prefer the random forest model. This algorithm also has a built-in function to compute the feature importance.
