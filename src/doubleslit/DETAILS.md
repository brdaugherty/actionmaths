# Double Slit Experiment: Probability and Wave-Particle Duality

This simulation demonstrates how probability dictates the behavior of quantum particles. While the landing spot of an individual particle appears random, the aggregate behavior of many particles reveals an underlying wave-like interference pattern.

## How Probability is Involved

In this simulation, probability acts as the "bridge" between the wave-like behavior of light and its particle-like behavior.

### 1. The Wave Defines the "Rulebook"
When you toggle the **Wave View**, you see overlapping ripples. Mathematically, these represent the **Wave Function**. 
- **Constructive Interference:** Where ripples overlap and amplify each other, the probability of a particle landing is high.
- **Destructive Interference:** Where ripples cancel each other out, the probability is zero.

### 2. The Particle Follows the "Dice"
Every time a **Single Photon** is fired, the simulation performs a "stochastic" calculation called **Rejection Sampling**:
1. The engine picks a random spot on the screen.
2. It checks the intensity (probability) at that specific spot based on the interference formula: $I \propto (\text{sinc}(\alpha))^2 \cdot (\cos(\beta))^2$.
3. It "rolls a die." If the random value is less than the intensity, the particle lands there. Otherwise, it picks a new random spot and tries again.

### 3. Emergence through Aggregate Choice
This is the core of the experiment:
- **Individual Level:** You cannot predict exactly where a single photon will land; it is a random event dictated by a roll of the "probability dice."
- **Aggregate Level:** Because the dice are weighted by the interference pattern, firing thousands of photons causes them to naturally cluster into the smooth wave-like pattern seen in the analytics chart.

## Mathematical implementation
The simulation uses the standard double-slit interference formula to calculate the probability distribution across the screen, then uses that distribution to bias the random landing spots of individual particles.
