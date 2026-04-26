# ActionMaths: Quantum Physics & Simulation Details

This document contains a deeper dive into the core physics concepts, mathematics, and insights that power the ActionMaths simulations.

## 1. The Particle *is* the Wave
One of the hardest hurdles in quantum mechanics is visualizing a photon. In our simulators, you will notice that the photon does not travel as a tiny, solid bullet, nor does it "surf" on top of a wave. **While it is traveling, it is 100% a wave of probability.** 

The "particle" version of a photon does not exist during transit; it only exists for a fleeting fraction of a millisecond when the wave crashes into something and is forced to localize. This is why the expanding probability wave and the localized particle share the exact same cosmic speed limit ($c$).

## 2. The Mind-Bending Scale of Cosmic Interference
In our `doubleslit` simulator, you observe interference patterns forming over a short distance. However, if we mathematically scale up the Double Slit experiment to a detector screen placed 1 light-year away, the physical distance between just *two* bright bands of interference would be over **4.7 billion kilometers**—wider than the radius of our entire Solar System. The sheer size of an un-collapsed probability wave over astronomical distances is staggering.

## 3. What Actually Constitutes a "Detector" (Decoherence)
In the `dysonsphere` simulator, the Dyson Sphere acts as the ultimate detector. A detector is not necessarily a digital scientific instrument; it is **any physical matter** (like a grain of dust, a planet, or an astronaut's visor) that interacts with the photon, irreversibly entangling its state with the macroscopic universe. 

* *Crucial Insight:* Photons cannot act as detectors for other photons. Because photons are massless bosons with no electric charge, they do not collide at normal energies. They pass right through each other like ghosts.

## 4. The Cosmic Lottery (The Intermediate Planet)
Our `cosmiclottery` simulator models what happens when a wave passes *through* matter without fully collapsing. 

If a probability wave grows to be 50 billion kilometers wide and washes over a planet floating in space, the wave does *not* automatically collapse into the planet. The wave represents probability, but the photon itself is a singular entity. The universe "rolls the dice" based on the cross-sectional surface area. If the planet loses the cosmic lottery, the photon ignores it completely, continuing as a wave to collapse "elsewhere" on the final screen.

## 5. 3-Dimensional Propagation & The Dyson Sphere Collapse
Physical probability waves do not ripple flatly like water in a pond; they expand as perfect, invisible 3-dimensional balloons. Our Dyson Sphere simulation proved this concept visually: a perfectly spherical wave expands outward until it physically touches the inner boundary of the 1-AU wireframe shell. The exact moment of contact forces the giant 3D wave to vanish instantly, localizing into a single geometric point on the shell. 

## 6. The V2.0 Unified Architecture: Hilbert Space & State Vectors
In classical physics engines, you write different code for different phenomena. In reality, the universe uses a single "engine" for everything: **Linear Algebra acting on a Hilbert Space**.

A Hilbert space is simply an abstract mathematical vector space that can accommodate complex numbers and infinite dimensions. In ActionMaths v2.0, we represent the entire state of a physical system as a single array of numbers (a State Vector, implemented via `Float32Array`). The physics you observe visually is entirely dictated by the *size* (dimensionality $N$) of this vector. As $N$ increases, the vector unlocks more complex degrees of freedom:

*   **Low Dimensionality ($N=2$):** The vector only has room to store simple scalar probabilities (Left vs. Right). The system behaves strictly classically (e.g., **Galton Board**).
*   **Medium Dimensionality ($N=100+$):** The vector is large enough to store complex numbers (Amplitude + Phase) across a spatial boundary. Because phase is tracked, probabilities can mathematically cancel each other out, and wave interference naturally emerges (e.g., **Double Slit**).
*   **High Dimensionality ($N=10^6+$):** The vector is massive enough to map to a dense 3D coordinate space. It represents a continuous spherical probability density function. A quantum "collapse" is simply the massive vector zeroing out everywhere except for a single index (e.g., **Dyson Sphere & Cosmic Lottery**).
*   **Tensor Space ($N \times N$ matrix):** The array no longer stores spatial coordinates, but rather the *correlations* (entanglement) between all nodes. Space and time are abandoned for pure network topologies (e.g., **Quantum Field Theory & Perspective Journey**).

When reading the JavaScript source code for these demos, pay close attention to the initialization of the `stateVector`. You are watching the universe literally "upgrade" its physics by simply adding more dimensions to an array.
