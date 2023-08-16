# Np-hard & P-hard



## the reason I want to understand clearly about Np and P

There are many papers I read before describe the problem they want to solve as Np-hard problems. However, everytime I look at those definition, I felt confusion. This pushes me to make out this question.


## mian


P is all search problems that can be solved in polynomial time, this is easy to understand. 

In my understanding, Np contains two features, search problems which contain any of them can be regarded as NP. The first feature is, have not yet found a way that can go through all possible solution, which means that there exist some solutions that have not yet been found; the second feature is, there is a way to go through all possible solution but it takes super long time e.g., exponential time. But think about it again, this two features can be regarded as one feature: if there exist one algorithm that can go through all possible solution and find a correct one in a `feasonable` time.

## related to my work - think about algorithm construction

If there are many problems belong to Np-hard, how to solve them?

The first general algorithm that goes in my mind is greedy. Here we don't need to search one by one, we search one and then jump some and search the next one following some trend. It kind of like use `accuracy` to transform `speed`. So it sometimes just drop on a local best location. To my best of knowledge, in network science, at least three papers use the similar thing to try to solve this problem - generic algorithm. The key in generic algorithm is although every time it use objective function to do the fitness, it also do crossover and mutation to kind of 'mix' the results, this way could try to avoid quickly stuck in a local best location. If I can think that greedy is a solution for a nondeterministic machine as 'guessing' the solution to a problem (then certifying that the solution is valid).

## philosophy problems

P = NP ?

my understanding for this equation is: proof a problem is not belong to P equals proof a problem is belong to NP.

However, I find there are some other explainations, for example, if Np = P, all search problems can be solved in polynomial time, otherwise, there are some search problems cannot be solved in polynomial time. 

Then my question is why the question P = Np exists? In order to solve what?

If P = Np is correct, then all search problems can be solved in an efficient way. There will be more and more algorithms and faster and faster?

If P = Np is not correct then there are some problmes cannot be solved for sure. So there will be a upper bound for the amount of problems being solved unless the keep updating hardwares?

---
date: 2023-08-15
---


