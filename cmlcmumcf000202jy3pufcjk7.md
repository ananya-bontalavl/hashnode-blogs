---
title: "What are Loss Functions?"
datePublished: Sat Feb 07 2026 18:13:33 GMT+0000 (Coordinated Universal Time)
cuid: cmlcmumcf000202jy3pufcjk7
slug: what-are-loss-functions
tags: data-science, machine-learning, engineering, loss-functions

---

A nice way to think about machine learning is to compare it to how we learn from our mistakes. In most ML setups, a model makes a guess, checks how wrong it was, and then tries to do a little better next time.

The Loss function aka the Error Function, takes the model’s prediction and the actual correct answer(the ground truth) and turns that into a single number. Bigger Number = worse prediction and smaller number = better prediction. Our goal here is to make that number smaller.

This reminds me of those weekly school tests. You give a test, get your results back and do an error analysis where you go through the questions where you messed up so that you would not repeat those mistakes again. Machine Learning is kind of like that, except the model does not see the solution or understand what it did wrong. It just gets a number to see whether it did “not that great” or “that was closer to what we intended”.

Next an optimization algorithm uses this number to adjust the model’s weights and biases so that the model performs better the next iteration. These iterations are repeated tens, hundreds of times depending on the model complexity, dataset size, and the model slowly gets better at the task because it pushes itself in the direction that makes the loss smaller.

In short Loss Function is like a feedback signal that tells the model how it’s doing and guides it towards making fewer mistakes over time.

This was just a short introduction to loss functions. Next, we’ll go into how they actually work and which loss functions are used in different scenarios.

A small heads-up, I’m planning to keep these posts short and bite sized. Rather than dumping everything in one huge article, I’ll break things into small pieces that are easier to read. The idea is to build things up slowly, one concept at a time.