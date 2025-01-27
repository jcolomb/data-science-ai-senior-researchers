---
title: "What is AI?"
teaching: 0
exercises: 0
questions:
- "What is AI and how can we define it?"
- "What types of AI exist and what doesn't exist?"
objectives:
- "Gain broad picture overview of AI and its history"
keypoints:
- "Three types of AI: Simulations, Symbolic, Machine Learning"
---

# Introduction

Machine learning is increasingly used in biomedical research, with more papers making big claims about AI. The growing role of AI in healthcare, policy, and fundamental biomedical/life sciences has great public interest. However, for scientists without specialist training the complexity and opaque use of buzzwords makes it difficult to know what to trust and where to begin. Researchers and funding bodies may want to explore new computational options for biomedical/life sciences, and this guide should provide a roadmap for the big picture view of what AI is, how it can be used in research, and how to critically assess the common problems that can arise. 

On the one hand, AI and machine learning can greatly improve the workflows in data processing and analysis, and can provide insight no human has time to achieve themselves. On the other hand, there are many limitations to what AI can do and is not magic. 



# What is AI?

 

Describing Artificial Intelligence is often more about what we *wish* existed rather than describing what actually exists. It can instead be more informative to describe the problems we can solve with Artificial Intelligence and how it is achieved. This is not a deeply technical introduction, instead it is written to describe case studies and overview. 

## What does not exist?

Siri and Alexa can answer simple instructions but use scripted interactions, there is not an understanding of the world like fictional intelligent robots. There is currently nothing close to Artificial General Intelligence, and we wouldn't know where to start in building it. The idea that a computer "understands" a problem is in a  narrow, technical sense, not the way a human understands. 

Chatbots can fool us into thinking there is understanding. 

> “I had not realized ... that extremely short exposures to a relatively simple computer program could induce powerful delusional thinking in quite normal people.”
>
> Author of Eliza, the first chatbot

## Types of AI that DO Exist

AI could be defined as anything done by a computer that would require intelligence if performed by a person. This is a useful but limited definition as it is difficult to properly define intelligence objectively. 

### Simulation

Also known as "running the equations", this may not seem like *real* AI. Simulations allow you to make predictions, which requires some sort of intelligence!

Predicting knowing where the planets will be in the solar system months or years in advance is possible because we know how the solar system works and can numerically simulate its working. 

Similarly, in cell automata we can set the rules of infection and susceptibility and watch how disease spreads between the neighbours over time steps. In this case, the susceptible cells are in blue, infected cells are white, and removed cells are red. We can adjust the model of the disease and the cell population to test the effects of disease spread. 

To create a simulation, you need to know exactly how the "world" works, also known as a model or a theory. Whether its Newtonian physics or the rules of infection or exactly the properties of stresses and strains on a steel bridge. You then need to know how the world is in a specific instance, so the model can be run forwards and learn what happens later. This knowledge is then captured by the computer.  

> **Case Study**
>
>At the Turing Institute, there are many projects which involve simulations and go under the term Digital Twin. These projects look at the major challenge of coping with uncertainty in our knowledge of the world. 



### Symbolic (Good Old Fashioned) AI

When we think of well known AI cases, we might think of Deep Blue, a chess playing AI from the 1990s. The first time AI beat a reigning world champion was in 1997, where Kasparov was defeated. To understand how AI like Deep Blue works, we can use an easier game to demonstrate how it works. 

In the game noughts and crosses (or tic-tac-toe), the objective is to alternate between two players, each of whom wants to get three of their counters in straight line. Using computational power, the AI can calculate all the probabilities of each possible move, and use this to determine the best move to make. 

Chess and noughts and crosses are micro-domain games, an extremely limited "world" that the computer works within. The position of the chess piece can be described precisely and completely. The rules of the movement and the final end goal is well defined and unambiguous. 

trying to use this kind of AI to recognise handwriting doesn't work. Imagine trying to completely describe the way 7 is written, the rules are too rigid and brittle to distinguish 1s and 7s, and may miss all the 7s with a slash through them. It couldn't possibly hope to recognise a cat. 

### Machine Learning

Instead, with machine learning the humans do not bother to try and find and apply rules. Instead, the computer finds its own rules. You start with a large dataset of known examples of the task we are trying to do. So in this case, 60,000 examples of handwritten digits, each one the same size. With this data set, it is labelled by a human and so every digit is "known". This becomes the training data set for the machine. When given a new, unknown example, the machine can look through the known examples to find the groups that the new digit most likely fits within. 

There are more complexities than this brief description, but machine learning fundamentally works this way. For all sorts of tasks, "big data" is becoming critical for machine learning. 

The machine does not "understand" the task, or know what handwriting is, the criteria for the solution is to match what the human labeller would classify the handwritten digit. 

Machine learning is already changing the way the world works. We can design novel architecture and quickly and cheaply ensure it will be structurally sound; your iPhone will find all photos of your kids with only a few examples; we can optimal driving directions within seconds, taking into account the current and predicted road conditions. It really is amazing, and only possible through breakthrough and year-on-year advances in principles, algorithms, and computer hardware.

# Summary

- AI can be defined as anything a computer can do would require intelligence if a human performed it. 
- Regardless of the type of AI, we are far from computers *understanding* the world or problems. 
- The first kinds of AI were simulations, which use equations to run a model forwards from a given state. 
- The next kind is Symbolic AI, which was used to beat the grand chess master in the 90s and works by calculating many eventualities in order to find the best solution. 
- The most recent type and one that has made huge leaps in recent years is Machine Learning.  

In the next episodes we will consider what tasks AI can do and its role in scientific research.

{% include links.md %}
