# Apriori & FPGrowth Algorithms:

**Apriori Algorithm:**

Apriori algorithm was the first algorithm that was proposed for frequent itemset mining. It was later improved by R Agarwal and R Srikant and came to be known as Apriori. This algorithm uses two steps “join” and “prune” to reduce the search space. It is an iterative approach to discover the most frequent itemsets.

Apriori says:

The probability that item I is not frequent is if:

P(I) < minimum support threshold, then I is not frequent.
P (I+A) < minimum support threshold, then I+A is not frequent, where A also belongs to itemset.
If an itemset set has value less than minimum support then all of its supersets will also fall below min support, and thus can be ignored. This property is called the Antimonotone property.

**FP-Growth Algorithm:**

This algorithm is an improvement to the Apriori method. A frequent pattern is generated without the need for candidate generation. FP growth algorithm represents the database in the form of a tree called a frequent pattern tree or FP tree.

This tree structure will maintain the association between the itemsets. The database is fragmented using one frequent item. This fragmented part is called “pattern fragment”. The itemsets of these fragmented patterns are analyzed. Thus with this method, the search for frequent itemsets is reduced comparatively.


## Reference:

https://www.softwaretestinghelp.com/fp-growth-algorithm-data-mining/

https://towardsdatascience.com/understand-and-build-fp-growth-algorithm-in-python-d8b989bab342
