![](Assets/SlidingP-001.png)

# The Sliding Picture Game written in Microsoft Power apps: Installation and Setup

This is a short (~3.5 minute) install and setup walkthrough for a Sliding Picture Puzzle game built in Microsoft PowerApps. The presenter covers what's included in the download (the .msapp file and a zip of image assets), explains that the image assets must be hosted somewhere accessible via URL (they use OneDrive), and shows how to grab the base URL path needed for configuration. They then demo the game itself — a classic 8-puzzle (3×3 grid with one blank tile) where players slide numbered or image-based tiles into order. The game features a live timer, swap counter, a confetti animation on completion, and an optional "More Information" button linking to an external URL. The video closes with a call to action to explore the creator's other PowerApps work and to like/share/subscribe.

YouTube Video: https://youtu.be/XDOuvzWEV_k 

# Code Overview

In this technical walkthrough, I go under the hood of the logic and code behind the game. I cover workarounds that are challenging for developers who come from procedural languages and robust IDEs—especially when handling the lack of native debugging and standard looping constructs.

**Key technical topics covered:**

- **Mathematical Solvability**: Using the "Inverse Check" to ensure every generated puzzle can actually be solved.
- **Simulated Looping**: Using Timer objects to replicate `while` and `repeat` functions for shuffling tiles.
- **UI Efficiency**: Referencing object properties instead of hardcoding values to create a maintainable grid.
- **Variable Architecture**: A breakdown of when to use Global vs. Context variables in a gaming environment.

YouTube Video: https://youtu.be/bqvlT9lHeYo
