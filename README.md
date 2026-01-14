# Physics for Creative Coders: Video 1 - Vector Flow Fields 🌊

Welcome to the first project in the "Foundations of Game Engines" series! In this project, we explore how to turn mathematical vectors into organic, wind-like movement using Vanilla JavaScript.

## 📁 Repository Structure

simple_flow.html: The clean, 50-line version we built in the video.

advanced_flow.html: The polished version featuring HSL color shifts and silky trails.

## 🧠 Key Concepts

- Vectors: Understanding magnitude and direction.

- Kinematics: The relationship between position and velocity.

- Trigonometry: Using Math.sin() and Math.cos() to create smooth force fields.

- Alpha Blending: Creating "Persistence of Vision" trails using RGBA.

## 🚀 The "Amlan Challenges"

Don't just copy the code—experiment with it!

### Level: Beginner (Aesthetics & Speed)

- The Ghost Mode: Change the background to a deep navy blue (#000033) and set the particles to pure white. Lower the trail opacity in fillRect to 0.02 for a ghostly, ethereal effect.

- Speed Demon: In the position update, multiply the vx and vy by 2 or 3. How does increasing the speed affect the "silkiness" of the trails?

- Thick Brush: In advanced_flow.html, find the ctx.lineWidth property. Increase it to 4 or 5. How does the "Art" change when the wind lines have more weight?

### Level: Intermediate (Chaos & Constraints)

- Turbulence: In the angle calculation (the part with Sin and Cos), multiply the final result by 20. Observe how the smooth flow breaks into high-energy turbulence.

- The Bounce: Instead of wrapping particles around the screen, modify the code so they reflect (bounce) off the edges of the canvas. (Hint: Multiply velocity by -1).

- Particle Decay: Give each particle a life property. Decrement it every frame and respawn the particle at a random location once its life reaches zero.

### Level: Advanced (Mathematical Systems)

- The Vortex: Can you modify the angle formula so all particles spiral toward the center of the screen? (Hint: Use Math.atan2(centerY - p.y, centerX - p.x) + Math.PI/2).

- Magnetic Pull: Use the distance formula to make the wind "bend" toward your mouse cursor as it moves across the screen.

- Speed-to-Hue Mapping: In the HSL version, map the Hue value to the particle's current velocity. Make faster particles "hotter" (Red/Yellow) and slower particles "cooler" (Blue/Purple).

## 📺 Watch the Tutorial

[\[YouTube Video\]](https://youtu.be/cSJq9anv8gI)

If this project helped you understand vectors a bit better, feel free to ⭐ the repo!

## 🔬 Try out the Labs

[\[Website\]](https://amlanpati.co.in/labs/vector-flow/)

Experiment with vector fields in real time using my interactive lab—adjust particle count, speed, frequency, and field equation.

## Connect with me:
[LinkedIn](https://www.linkedin.com/in/amlan-pati/) | [Instagram](https://www.instagram.com/theAmlanPati/) | [Twitter](https://x.com/TheAmlanPati)