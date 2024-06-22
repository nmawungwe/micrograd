# Understanding Backpropagation: My Journey with the Chain Rule

Hey there! I've been diving into how neural networks actually learn, and I want to share what I've discovered about backpropagation and the chain rule.

## What I Learned

Backpropagation is how neural networks learn. It's basically just applying the chain rule from calculus over and over through the network.

## The Chain Rule

Remember the chain rule? It goes like this:

If y = f(u) and u = g(x), then:
dy/dx = dy/du * du/dx

This simple rule is super important for how neural networks figure things out.

## What I Did

I created a Python class called `Value` to represent each part of a neural network's computation. Each `Value` knows how to do basic math operations and how to calculate gradients for backpropagation.

The cool part is that when you do operations with `Value` objects, it automatically sets things up for backpropagation later.

## Seeing is Believing

To really understand what was happening, I made a function to draw the computation graph. It shows how all the numbers and gradients flow through the network. This helped me visualize the chain rule in action.

## Why It Matters

Getting hands-on with this stuff helped me:
1. Actually understand how neural networks learn
2. See how to debug and improve neural networks
3. Get ready for more advanced machine learning ideas

## Want to See More?

I've put all my code on GitHub. You can find:
- The `Value` class I made
- Examples of forward and backward passes
- The code for drawing computation graphs
- A simple neural network I built
