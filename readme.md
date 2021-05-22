# Pokémon: gotta catch'em all!!

Hello again! Following last week's project, let's analyse our Pokémon data set and do some statistics analysis. For that, we'll calculate some stats, and support our conclusion with some data visualization.

**We'll explore:**

+ Strongests Pokémon: clustering

+ Type distribution

+ Catch rate


**Summary:**

In this brief study, we've segmented our Pokémons based on the sum of their different statistics:

- hp
- attack
- defense
- sp_atk
- sp_def
- speed

Then, we've identified Mewtwo as (by far) the strongest Pokémon of all. Therefore, we've isolated him from the remaining one. Afterwards, we've proceeded with a preliminar clusterization based on the values of the quartiles, using an empirical rule of the distance of interquartiles.

Identifying a subset of 70% of the 150 Pokémon, we've normalised the data in order to apply the segment the population, and thus, clusterise this subset. Finally, we've added this clusterization to the whole dataset and observed the distribution of this classification over the type_1 and catch rate.