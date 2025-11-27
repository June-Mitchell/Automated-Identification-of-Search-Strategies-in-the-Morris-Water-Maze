# Automated-Identification-of-Search-Strategies-in-the-Morris-Water-Maze
This project develops an automated and objective method for classifying search strategies used by mice in the Morris Water Maze (MWM). Using coordinate data extracted from AnyMaze tracking, the system quantifies spatial behavior through geometric, polar, and zone-based metrics, including ring occupancy, polar coverage, platform-zone engagement, path straightness, and goal-corridor following.

Based on these features, the algorithm classifies each trial into established allocentric and egocentric strategies—such as direct swim, focal search, random search, thigmotaxis, chaining, and scanning—and identifies perseverance during reversal learning. The pipeline processes all trials, generates visual summaries of strategy evolution across days and trials, and produces detailed mouse-by-trial strategy tables for statistical analyses.

In parallel, this project implements an unsupervised learning module that clusters trajectories using PCA-reduced features and k-means, enabling data-driven identification of behavioral patterns. It includes an interactive Plotly viewer where clicking on any point reveals the full trajectory overlaid on the water maze, allowing intuitive exploration of clusters and behavioral differences.

This software was developed by June Mitchell, Yadu Gopakumar and Luke King during the Python Applications for
Neuroscience Research course, Université Paris Cité, 2025. © 2025 The contributors.
Released under the MIT License.
