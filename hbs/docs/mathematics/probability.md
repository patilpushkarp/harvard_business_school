# Probability

## Experiments, Sample Spaces and Events

- For any experiment, outcome is uncertain.
- **"Sample Space - The set of all possible outcomes for an experiment."**
- A set of possible outcomes i.e. a subset of points in a sample space in a probabilistic experiment is called an event.

## Calculations involving sample spaces
- The total probability of all points in a sample space adds up to 1.

## Mutually Exclusive Events

- **"Mutually Exclusive Events - A set of events are mutually exclusive if the occurrence of one event precludes the occurrence of any other event."**
- If the events are mutually exclusive then, $P(E_1$ or $E_2) = P(E_1) + P(E_2)$
- If the events are not mutually exclusive then, $P(E_1$ or $E) = P(E_1) + P(E_2) - P(E_1$ and $E_2)$.

## Complimentary Events

- **"Two events are complementary events if they have no points in common and together include all points in an experiment's sample space."**
- The complement of event $E$ is $\bar{E}$.
- $E$ and $\bar{E}$ are mutually exclusive events.
- $P(E$ or $\bar{E}) = 1 = P(E) + P(\bar{E})$.

## Conditional Probability

- **"Given two events $A$ and $B$ the conditional probability of event $A$ given that event $B$ has occurred is written as $P(A|B)$. Intuitively, once we know that event $B$ has occurred, this is the chance that event $A$ will occur."**
- $P(A|B) = \frac{P(A and B)}{P(B)}$
- **"Given two events A and B we define the joint probability of A and B to be the probability that events A and B both occur."**

## Independents Events

- **"Independent Events - Two events are independent if the occurrence of one of the events does not change our estimate of the probability of the other event. In short, events A and B are independent if and only if P(A|B) = P(A)."**
- For two independent events $E_1$ and $E_2$, $P(E_1$ and $E_2) = P(E_1) \times P(E_2)$

## Random Variables

- **"Random Variable - A function that associates a numerical value with every possible outcome of an experiment."**
- Random variables can be discrete or continuous.
- **"Expected Value of a Random Variable - The average value you would expect to see of a random variable if you perform an experiment many times."**
- **"The expected value of a discrete random variable is found simply by multiplying each value of the random variable by its probability and then adding up the products."**
- For discrete random variables, $E(X) = \sum_{i=1}^{n} p_i x_i$.
- **"The expected value of a discrete random variable tells you, on average, what value that variable has."**
- **"Variance of a Random Variable - A measure of a random variable's spread about its mean defined as the average squared deviation of a random variable from its mean. $\sigma^2(X) = \sum_{i=1}^{n} p_i (x_i - E(X))^2$."**
- The standard deviation of a random variable $\sigma(X)$ is simply the square root of the variance. 

## Continuous Random Variables

- **"Continuous Random Variable - A continuous random variable is used to describe an uncertain quantity (such as height, weight, or return on a stock) which can assume an infinite number of values and is defined over an interval or intervals of values."**
- **"Probability density function (PDF) - A continuous random variable's pdf tells us the relative likelihoods of the random variable's possible values. The area under a pdf between a and b is the probability that the continuous random variable assumes a value between a and b."**
- A PDF has the following properties:
  - It is always nonnegative.
  - The height of a PDF for a value x of a continuous random variable represents the relative likelihood that the random variable assumes a value near x.
  - The total area under the PDF must equal 1.
  - The probability of an event involving a continuous random variable corresponds to the area under the PDF. The total probability of all possible outcomes must equal 1, in line with the total area of 1 under the PDF.

## Normal Random Variable

- **"Normal Random Variable - A continuous random variable that describes many quantities such as height, weight, or monthly sales of a product. A normal random variable is specified by its mean and standard deviation. The Excel function =NORMDIST(x, mean, standard deviation, True) gives the probability that a normal random variable with a given mean and standard deviation is ≤ x."**
- **"The normal random variable, often called the bell curve, has the following PDF: $f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{- \frac{(x - \mu)^2}{2 \sigma^2}}$. Where, $e=2.7182$."**
- The normal random variable has several important properties:
  - A normal random variable assumes a mean value μ.
  - A normal random variable has a variance of $\sigma^2$ and a standard deviation of $\sigma$.
  - There is a 68% chance that a normal random variable assumes a value within σ of the mean, a 95% chance that it assumes a value within 2σ of the mean, and a 99.7% chance that it assumes a value within 3σ of the mean.
  - The normal PDF is symmetric about the mean: It looks the same to the left of the mean as it does to the right.
