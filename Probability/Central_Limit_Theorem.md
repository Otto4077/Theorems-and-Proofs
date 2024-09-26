# Central Limit Theorem (CLT)

## Definition
The Central Limit Theorem states that if \( Y_1, Y_2, \ldots, Y_n \) are independent random variables drawn from a population with any probability distribution that has a finite mean and variance, then the distribution of the sample mean \( \bar{Y} \) will approximate a normal distribution as the sample size \( n \) becomes large.

## Formula
The sample mean \( \bar{Y} \) is calculated as:

\[
\bar{Y} = \frac{1}{n} \sum_{i=1}^{n} Y_i
\]

- **Mean of \( \bar{Y} \)**: \( E(\bar{Y}) = E(Y) \)
- **Variance of \( \bar{Y} \)**: \( Var(\bar{Y}) = \frac{\sigma^2(Y)}{n} \)

## Key Points
1. **Approximate Normal Distribution**: For a large enough sample size \( n \), the distribution of the sample mean \( \bar{Y} \) will be approximately normal, regardless of the shape of the original population distribution.

2. **Convergence**: The larger the sample size \( n \), the closer the sample mean distribution will be to a normal distribution.

3. **Implications**: This theorem allows us to use normal probability models to make inferences about population means and sums, even if the population itself is not normally distributed.

## Practical Example
- If you repeatedly sample a large number of people's heights from any city, and calculate the average height for each sample, those averages will form a normal distribution, even though individual heights may vary widely.

## Applications
- **Hypothesis Testing**: CLT is fundamental for constructing confidence intervals and conducting hypothesis tests for population means.
- **Quality Control**: Used in manufacturing to ensure that processes remain consistent over time.

## Assumptions
1. **Independence**: The sampled observations must be independent of each other.
2. **Sample Size**: The sample size should be sufficiently large (usually \( n > 30 \) is considered adequate).
3. **Finite Variance**: The population from which samples are drawn must have a finite variance.

## Visualization
Below is a typical representation of the Central Limit Theorem, where the distribution of the sample means becomes approximately normal as \( n \) increases:

