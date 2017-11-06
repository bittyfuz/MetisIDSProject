# Metis Introduction to Data Science Course Project
----
The data set I am studying includes features which are conditions of sunspots before a solar flare erupts, with the target being the class of the solar flare.

With this data, I'd like to find out what features are most/least important for predicting the class of solar flare, and to find out how reliably I can predict the class.

So far, what I know about this data is that magnetic fields on the Sun cause sunspots and solar flares, so I expect that conditions of sunspots are correlated with the strength solar flare activity and can hopefully predict it fairly accurately.

I do astrophysics (cosmology), and I did a small project on space weather before, so this data set looked interesting to me.

[Link to site where I grabbed the dataset](http://archive.ics.uci.edu/ml/datasets/Solar+Flare)

[Data Set](flare.data2.txt)

[Description of Data Set](flare.names.txt)

[Notebook with analysis](IDSproject.ipynb)

****
----
Questions/Problems:

* There are only 4 observations of one of the classes (the most extreme flares), should I not include those flares?

* How could I take into account that I'm actually given the *number* of flares in each class? I feel like I'm throwing away information that could be useful.

* Why should I drop the last category when I replace categorial data with dummy arrays? 
 * How can I interpret how important that feature would have been?

* What's a good way to visualize categorical features?

* What's a good way to visualize the results of linear regression and random forest?

For the future:

* Would be nice to have more clarification on what some of the features really mean. 
 * Some columns don't make much sense to me
  * area, l\_area, hist\_complex, activity (why no increase value?)

* More data. Only had ~1100 observations from 3 months in the 80's - which means there should be a **ton** of data now.
