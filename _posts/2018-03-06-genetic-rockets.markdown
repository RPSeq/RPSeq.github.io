---
layout: post
title: "Genetic Rockets"
date: 2018-03-06 06:39:47 -0600
categories: js
js_libraries:
- p5
- p5.dom
custom_js:
- SmartRockets/dna
- SmartRockets/population
- SmartRockets/rocket
p5_sketch:
- SmartRockets/sketch
---


Having no experience with JavaScript, I took an existing [TheCodingTrain](https://thecodingtrain.com/CodingChallenges/029-smartrockets.html) project that simulates a population of rockets with individual genomes and added logic to control how many simulation cycles run between each rendered frame, allowing you to manipulate the "speed" of evolution.  Genomes consist of a series of force vectors applied to the rocket at each frame. Rockets that get near the target have a fitness bonus, and rockets that reach the target even more so. Speed things up to see how your rockets evolve! This was mostly an exercise to learn some JavaScript basics, as well as learning how to embed JavaScript apps in Jekyll blog posts. Work in progress. (Updated 3-14-2018)
