---
layout: post
title:  Egret Swarm Optimization Algorithm (ESOA)
date:   2017-05-26 14:05:55 +0300
image:  assets\images\Algorithms\ESOA\egret.jpg
author: Knightsll
tags:   Algorithm
---

**Egret Swarm Optimization Algorithm (ESOA), The Egret Swarm Optimization Algorithm (ESOA) is a meta-heuristic algorithm that combines the predatory behavior of Snowy Egrets (Sit-And-Wait Strategy) and Great Egrets (Aggressive Strategy).**

### Inspiration


Among the egret family, the Snowy Egret and the Great Egret are two species that differ considerably in their feeding behavior. The Snowy Egret applies the least energy-intensive sit-and-wait strategy: it stands still and waits patiently, watching for prey until it appears and then darting to grab it with its beak. Snowy egrets that use the sit-and-wait strategy tend to retrieve relatively steady gains with very low energy consumption. Great egrets, on the other hand, are aggressive, and once they have spotted their prey, they will chase it until it is caught. The aggressive strategy is energy-intensive, but it also allows the Great Egret to potentially achieve higher returns. Inspired by the predatory behavior of snowy egrets and great egrets, an algorithm ESOA that combines the advantageous characteristics of both is proposed.

### Mathematical Model
<img src="\assets\images\Algorithms\ESOA\Framework.png" width = "100%" height = "100%" alt="Framework" align=center />

The ESOA consists of three main components: a sit-and-wait strategy, an aggressive strategy, and a discriminant condition. Each egret swarm can consist of n egret squads, each of which in turn contains three egrets, with Egret A implementing the sit-and-wait strategy and Egret B and Egret C using the random walking and encircling mechanisms of the aggressive strategy, respectively.

#### Sit-And-Wait Strategy
<img src="\assets\images\Algorithms\ESOA\saws.png" width = "100%" height = "100%" alt="Framework" align=center />

#### Aggressive Strategy
<img src="\assets\images\Algorithms\ESOA\as.png" width = "100%" height = "100%" alt="Framework" align=center />

#### Discriminant Conditions
<img src="\assets\images\Algorithms\ESOA\dc.png" width = "100%" height = "100%" alt="Framework" align=center />

### Experiment Result

To verify the effectiveness of the algorithm, the following three typical test functions were used and compared with five state-of-the-art optimization algorithms.

Sphere Function (n=30):

<img src="\assets\images\Algorithms\ESOA\F1.png" width = "50%" height = "50%" alt="Framework" align=center />


Schwefel&#39;s Problem 2.21(n=30):

<img src="\assets\images\Algorithms\ESOA\F4.png" width = "50%" height = "50%" alt="Framework" align=center />


Quartic Function i.e (n=30):

<img src="\assets\images\Algorithms\ESOA\F7.png" width = "50%" height = "50%" alt="Framework" align=center />


### Algorithm Code
[Python Code](https://github.com/Knightsll/Egret_Swarm_Optimization_Algorithm)

[MATLAB Code](https://ww2.mathworks.cn/matlabcentral/fileexchange/115595-egret-swarm-optimization-algorithm-esoa)


### Reference
[1] Egret Swarm Optimization Algorithm: An Evolutionary Computation Approach for Model Free Optimization，submitted to "Mathematics".























