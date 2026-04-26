# Galton Board: The Central Limit Theorem in Action

The Galton Board (or Quincunx) is a physical and mathematical demonstration of how order emerges from chaos. It illustrates the **Central Limit Theorem**, showing that the sum of many independent random variables tends toward a normal distribution (the "Bell Curve").

## How Probability is Involved

In this simulation, every ball's journey is a series of individual probabilistic events that aggregate into a predictable statistical pattern.

### 1. The Bernoulli Trial (The Peg)
Each peg represents a binary choice. When a ball hits a peg, it has exactly a **50% chance** of bouncing left and a **50% chance** of bouncing right. Mathematically, this is a **Bernoulli Trial**.

### 2. The Binomial Distribution (The Journey)
A ball's final position is determined by the total number of "right turns" it takes across the 10 levels of pegs. 
- If it takes 0 right turns, it lands in the leftmost bucket.
- If it takes 10 right turns, it lands in the rightmost bucket.
- Most balls will take roughly an equal number of left and right turns, landing in the middle.

The probability of landing in bucket $k$ out of $n$ levels is given by the **Binomial Distribution** formula:
$$P(k) = \binom{n}{k} p^k (1-p)^{n-k}$$
where $n=10$ and $p=0.5$.

### 3. Emergence of the Normal Distribution
As you drop hundreds of balls, the discrete binomial distribution begins to smooth out. According to the **Central Limit Theorem**, as the number of independent trials increases, the distribution of their sum approaches a **Normal Distribution**.

## Advanced Statistical Features
- **Ghost Curve:** The white overlay represents the *theoretical* distribution. It shows you exactly where the balls "should" land according to the math.
- **Heatmap (Z-Scores):** The buckets change color based on their **Z-score**—a measure of how many standard deviations the actual count is from the expected mean. 
    - **Green:** Close to the predicted probability.
    - **Yellow/Red:** Statistical outliers (deviating significantly from the expected pattern).
- **Relational Tones:** The sound frequency increases for buckets further from the mean, using audio to reinforce the concept of statistical distance.
