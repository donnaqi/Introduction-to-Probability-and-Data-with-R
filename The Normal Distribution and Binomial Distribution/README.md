# Normal Distribution

## 1. Standardized (Z) Score 
Standardized (Z) score of a data point as the number of standard deviations it is away from the mean: Z = (observation - mean) / SD
```
Z = (x − μ ) / σ
```

## 2. Use the Z score 

If the distribution is normal: using technology or normal probability tables to determine the percentile score of a data point

- Distribution Calculator and choose Normal:
https://gallery.shinyapps.io/dist_calc/

- R:
    ``` 
    Calculate percentile:
    > pnorm(observation x, mean = μ, sd = σ)
    ```

    ```
    Calculate observation:
    > qnorm(percentile, mean = μ, sd = σ)
    ```

- Normal probability tables:
https://drive.google.com/file/d/1CmcRQ1foAtvBVCqzjhcvGe9mfpGVQ1zI/edit

Unusual: 
Regardless of the shape of the distribution, more than 2 standard deviations away from the meanis considered to be unusual

## 3. Mean and Medium
- Mean always has a Z score of 0
- Medium: Depending on the shape of the distribution

## 4. Evaluate Normal Distribution:
Assess whether or not a distribution is nearly normal using:
- the 68-95-99.7% rule 
<div align="center">
<img src= "https://miro.medium.com/max/1838/1*IZ2II2HYKeoMrdLU5jW6Dw.png" width=60%>
</div>


- graphical methods such as a normal probability plot 
<div align="center">
<img src= "https://researchhubs.com/uploads/evaluating-normal-distribution-1.png" width=60%>
</div>


# Binomial Distribution
## 1. Binomial

Determine if a random variable is binomial using the four conditions:

- The trials are independent.

- The number of trials, n, is fixed.

- Each trial outcome can be classified as a success or failure.

- The probability of a success, p, is the same for each trial.

## 2. Number of Possible Scenarios
Calculate the number of possible scenarios for obtaining x successes in n trials using the choose function: 

<div align="center">
<img src= "https://miro.medium.com/proxy/1*rjxvbR1YNhWVR-BWC0nlPg.png" width=60%>
</div>

Use R:
```
> choose (n, x)
```

## 3. Binomial Distribution Formula
Calculate probability of x successes in n trials using the binomial distribution: 

Number of scenarios * P(single scenario)

<div align="center">
<img src= "https://i.stack.imgur.com/Qurry.png" width=60%>
</div>

Use R:
```
> dbinom(x, size = n, p = prob)
```

Use Distribution Calculator and choose Binomial:
https://gallery.shinyapps.io/dist_calc/

## 4. Expected number of successes and Standard Deviation 
Calculate the expected number of successes in a given number of binomial trials:
```
μ = np
``` 

And its standard deviation:
```
σ = sqrt(np(1−p))
```

## 5. Use Normal Approx to Calculate Binomial

When number of trials is sufficiently large (np ≥ 10 and n(1−p) ≥ 10), use the normal approximation to calculate binomial probabilities, and explain why this approach works.

R:
```
> sum(dbinom(range x1:x2, size = n, p = prob))
```