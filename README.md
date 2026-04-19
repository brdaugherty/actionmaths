# actionmaths
Maths in action

Concepts and theory, visualized. Simply, act to know.

#### Galton Board Simulator
**👉 [Play the Live Demo here!](https://brdaugherty.github.io/actionmaths/src/galton/)**

A [Galton board](https://en.wikipedia.org/wiki/Galton_board) shows how a bell curve forms over time from simple random choices for a ball to go left or right. This simulation visualizes the Central Limit Theorem in real-time, featuring a mathematical "ghost curve" overlay and live Z-score heatmap coloring.

This simulator runs fully in your browser, as a single HTML page.
* **To run locally:** Download the [source file](src/galton/index.html?raw=true), usually right click and "save link as".
* Drag-and-drop the downloaded file into a new tab in your browser.
  
  This loads the page and runs the code.
* Press the **Spacebar** or **tap the board** a few times to drop a ball. Hold it down to drop a stream.

  Turn on your sound.
* To make changes visible only to you:
  * modify the downloaded file in your favorite editor
  * save and reload the tab in your browser

#### Double Slit Experiment Simulator
**👉 [Play the Live Demo here!](https://brdaugherty.github.io/actionmaths/src/doubleslit/)**

The [Double-slit experiment](https://en.wikipedia.org/wiki/Double-slit_experiment) demonstrates wave-particle duality, showing how probability dictates quantum mechanics.

This interactive simulation visualizes the intense math behind wave interference and particle distribution using pure, native browser APIs.
* **To run locally:** Download the [source file](src/doubleslit/index.html?raw=true), usually right click and "save link as".
* Drag-and-drop the downloaded file into a new tab in your browser.
* Click **Fire Single Photon** to shoot one particle at the screen.
* Click **Toggle Continuous Stream** to watch the classical interference pattern organically build up over time.
* Click **Toggle Wave View** to visualize the invisible, overlapping ripples causing the pattern.
* Adjust the **Wavelength ($\lambda$)** and **Slit Separation ($d$)** sliders to instantly see the math update the live probability distribution graph!

#### Quantum Wave Collapse (Dyson Sphere) Simulator
**👉 [Play the Live Demo here!](https://brdaugherty.github.io/actionmaths/src/dysonsphere/)**

This immersive 3D simulation explores the exact moment of wavefunction collapse. By scaling the thought experiment up to astronomical proportions (1 AU), it visualizes how a 3-dimensional probability wave propagates outwardly from a star before instantly collapsing into a single, localized particle upon interacting with a massive detector shell.

Built entirely in the browser using Three.js, it natively handles complex 3D rendering and particle math.
* **To run locally:** Download the [source file](src/dysonsphere/index.html?raw=true), usually right click and "save link as".
* Drag-and-drop the downloaded file into a new tab in your browser.
* Use **Left-Click to Rotate**, **Right-Click to Pan**, and **Scroll to Zoom** to explore the 3D space.
* Hit **Spacebar** to fire expanding probability waves from the central star.
* Watch the moment of detection trigger a brilliant, expanding flash on the wireframe shell.

#### The Cosmic Lottery (Probability) Simulator
**👉 [Play the Live Demo here!](https://brdaugherty.github.io/actionmaths/src/cosmiclottery/)**

A conceptual expansion of the Dyson Sphere simulator that visually answers the question: *What happens when a probability wave hits an object but doesn't collapse?*

This simulator places an intermediate planet halfway between the star and the Dyson Sphere. As the probability wave sweeps over the planet, the physics engine rolls a 100-sided die based on the planet's surface area. 
* **If it hits (15% chance):** The massive wave instantly collapses and flashes entirely onto the planet.
* **If it misses (85% chance):** The wave completely ignores the planet and passes through unharmed, collapsing "elsewhere" on the outer Dyson shell.

* **To run locally:** Download the [source file](src/cosmiclottery/index.html?raw=true), usually right click and "save link as".
* Drag-and-drop the downloaded file into a new tab in your browser.
