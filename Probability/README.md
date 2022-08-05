# Defining Probability

## 1. Probability of events

- probabilities of events: 
    - 0 <= P(A) <= 1
    - proportion of times the outcome would occur if we observed the random process that gives rise to it an infinite number of times

- frequentist interpretation: 
    - traditional definition of probabilities
    - the probability of an outcome is the proportion of the times the outcome would occur if we observed the random process an infinite number of times

- Bayesian interpretation:
    - a subjective degree of belief
    - separate people could have different viewpoints and so assign different probabilities to it
    - allow prior information to be integrated


## 2. The law of large numbers
The long-run relative frequency of repeated independent events settles down to the true probability as the number of trials increases </br>

Misunderstanding of the law of large numbers: gambler's fallacy, or the law of averages


## 3. Disjoint (mutually exclusive) 
Disjoint events as events that cannot both happen at the same time: 

If A and B are disjoint: 
```
P(A and B) = 0
```

Union of disjoint event: 
```
P(3 or Jack) = P(3) + P(Jack)
```


Union of non-disjoint event: 
```
P(red or Jack) = P(red) + P(Jack) - P(red and Jack)
```

General addition rule:

```
P(A or B) = P(A) + P(B) - P(A and B)
```

## 4. Distinguish between disjoint and independent events. 

If A and B are independent, then having information on A does not tell us anything about B (and vice versa).

i.e. Outcomes of two coin tosses are said to be independent.

General rule to check for indenpendence:
```
P(A | B) = P(A), then A & B are independent since 'given B' has no effect on probability of A
```

If A and B are disjoint (mutually exclusive), then knowing that A occurs tells us that B cannot occur (and vice versa).

```
P(A & B) = 0, then A & B are disjoint since the A and B can't happen at the same time
```

Disjoint events are always dependent since if one event occurs we know the other one cannot.

i.e. outcomes of two draws from a deck of cards, without replacement are dependent


<div align="center">
<img src= "https://keydifferences.com/wp-content/uploads/2016/05/mutually-exclusive-vs-independent-event.jpg">
</div>

## 5. Probability distribution 

list of the possible outcomes with corresponding probabilities that satisfies three rules: 

The outcomes listed must be disjoint.

Each probability must be between 0 and 1.

The probabilities must total 1.

## 6. Complementary outcomes 
complementary outcomes  : mutually exclusive outcomes of the same random process whose probabilities add up to 1 

If A and B are complementary, P(A) + P(B) = 1

Complimentary events are always necessarily disjoined

Disjoined events are not necessarily always complimentary

## 7. Distinguish between union of events (A or B) and intersection of events (A and B).

Calculate the probability of union of events using the (general) addition rule:

If A and B are not mutually exclusive:
```
P(A or B) = P(A) + P(B) − P(A and B) 
```

If A and B are mutually exclusive:
```
P (A or B) = P (A) + P (B), since for mutually exclusive events P(A and B) = 0 
```

Calculate the probability of intersection of independent events using the multiplication rule:

If A and B are independent:
```
P(A and B) = P(A) × P(B) 
```

If A and B are dependent:
```
P(A and B) = P(A|B) × P(B) 
```

# Conditional Probability

## 1. Marginal vs Conditional probabilities

Marginal Probabilities:


Conditional Probabilities:


## 2. Tree diagrams 
to calculate conditional probabilities and probabilities of intersection of non-independent 
Bayes’ theorem: P(A|B) = P(A and B) / P(B)

- Setting a prior
- Collecting data
- obtaining a posterior
- Updating the prior with the previous posterior

​
