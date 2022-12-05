---
layout: post
title:  "Intro to graph search algorithms!"
---

# Week 1 Notes

## Definitions 
**What is intellligence?**
The ability to aquire knowledge and apply the aquired knowledge to solve problems.

**What is artificial intellegence**
Intellegence machines used to solve problems.

**Rational Systems**
Systems that will always make rational descisions and use logic to achieve goals 

**Different Environments**
1. Episodic vs sequential 
    - Descision making is perfromed on each episode, like finding defective parts on an essembly line (simpler)
    - Descision making is perfromed based on a sequential manner, like finding the best path from start to end waypoints

**Adaptation** 
With dynamic environments, it is useful for the agent to improve over time, (evolve, learn)

**Cooperation**
-Agents share inforamtion (cooperate) to solve a problem

## Types of problems
1. Well-Structured 
2. Moderately-Structured
3. Ill-Structured 

|                 | Well-Structured           | Moderately-Structured | Ill-Structured           |
|-----------------|---------------------------|-----------------------|--------------------------|
| Goals           | well defined              | usually well defined  | undefined                |
| Beginning State | well defined              | well defined          | well defined             |
| Actions         | well defined              | many                  | undefined                |
| End State       | well defined              | well defined          | undefined                |
| Constraints     | well defined              | usually well defined  | usually not well defined |
| Example         | How to to zip up a jacket | replacing car engine  | designing a rocketship   |


## Problem Formulation
1. State Space
2. Initial State
3. Goal state
4. Actions
5. Cost


This webpage will discuss the following graph search algorithms alongside their code implementation:
1. [Breath First Search](#breath-first-search)
2. Depth Fist Search
3. Uniform Cost Search Greedy Search 
4. Greedy Search
5. A* 
6. Greedy A* 
6. Curvy A*


# Breath first search




