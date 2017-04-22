## 1. Bayes Theorem

### Conditional Probability:

- probability
- conditional probability 
- bayes theorem
- bayesian statistics

a) a probability is a number between 0 and 1 [0, 1]. 

b) a conditional probability, is a probability based on some background information.
   Example: we want to know the probability of Tomas having kids,
   at 45 years of age. According to statistics from SSB, 23% of men in Norway will
   not be fathers at that age. We wil assume that the male population under 45
   in Norway is 2 million. Tom is not random lets say Tom has some factor in his 
   favour for example he might be married, this might affect how likely Tom is
   not to be a father by 45. Notation for conditional probability is

   p(A|B) probability of A given that B is true.

c) cojoint probability - the probability that two things are true.
   - p(A and B)  = p(A) * p(B)   WARNING: not always true
   - only works if A and B are independent: p(B|A) = p(B) 

   - A rains today, B means that i rains tomorrow, if it rains today it is more likely that it rains tomorrow. so
   - p(B|A) > p(B)

   - p(A and B) = p(A)p(B|A) 


### The cookie problem


d)  the diachronic interpretation
    - update probability of a hypothesis H, in light of new data D.
    - diachronic - something happening over time
    - probability of H changes over time as we get new D

    p(H|D) = (p(H)p(D|H))/p(D)

    -p(H) = probability of hypothesis before we have data - prior probability
    -p(H|D) = what we want to compute - posterior
    -p(D|H) = likelihood
    -p(D) = normalizing constant

suite = set of hypotheses : mutulually exclusive, collectively exhaustive

p(D) = p(B1)p(D|B1)+p(B2)p(D|B2)


### The M&M problem


