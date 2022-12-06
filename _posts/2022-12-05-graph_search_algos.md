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
1. State Space: the environment that an agent is working in 
2. Initial State
3. Goal state
4. Actions
5. Cost

# Search Algorithms 
d - branching factor: the maximum number of successors that exiting a node 

**4 properties of search algorithms** 
- Completeness: Is the algorithm garenteed to find a solution 
- Optimality: Is the algorithm garenteed to find the best (shortest) path to the goal
- Time Complexity: How many nodes are generated/ how many computations are computed 
- Space Complexity: The memory used to store the all nodes

## Breath first search
- Search the tree layer by layer (FIFO)
Time Complexity: O(b^{d+1}) 
Space Complexity:
Completense:
Optimality: 
![Drag Racing](/test.png)


## Uniform Cost Search
- Put nodes in fringe and sort them, then pick node with lowest cost to expand
Time Complexity: 
Space Complexity:
Completense:
Optimality: 

## Depth First Search
- Deep first (FILO)
Time Complexity: 
Space Complexity:
Completense:
Optimality: 

## Depth Limited Search
- Limit the depth of the tree 
Time Complexity: 
Space Complexity:
Completense:
Optimality: 

## Iterative Deepening Search
- Iterativly increase the depth of the tree
Time Complexity: 
Space Complexity:
Completense:
Optimality: 

## Best First Search
- Limit the depth of the tree 
Time Complexity: 
Space Complexity:
Completense:
Optimality: 


## Greedy Search
- Limit the depth of the tree 
Time Complexity: 
Space Complexity:
Completense:
Optimality: 

## A* Search
- Limit the depth of the tree 
Time Complexity: 
Space Complexity:
Completense:
Optimality: 