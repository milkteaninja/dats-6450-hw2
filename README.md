# dats-6450-hw2
Introduction: The purpose of this homework will be to identify potential jargon. In order to accomplish this we will employ two small small document corpora. One will be related to news and the other will be from government documents. Your task will be to implement a simple jargon identifier.

In order to accomplish this task you will need to perform several steps. The first relates to identifying the word distributions in the base corpus. We will be using the Reuters news corpus as it is freely available in NLTK. For a jargon corpus we will be making use of DOD OIG reports that we have seen in the past. 

A first step will be to tokenize the documents in both sets. Then, you will try to simply look at the differences in tokens seen. 

But just looking at token differences isn't very sophisticated. We will also try to compare the probability of tokens occuring in each corpus as a mechanism to evaluate which tokens might be jargon.
