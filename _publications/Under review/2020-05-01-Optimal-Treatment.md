---
title: "OPTIC: Optimal Treatment Policy using Reinforcement Learning and Structural Causal Model"
collection: publications
permalink: /publication/2020-05-01-Optimal-Treatment
excerpt: ''
date: 2020-05-01
venue: 'Under review(IJCAI)'

---

We address the problem of optimal treatment policy recommendations for clinical applications. The current gold standard for 
designing and testing treatment policies is primarily based on randomized controlled trials (RCTs). Treatment policies 
inferred from RCTs might be sub-optimal due to small sample size and/or transportability issues. Motivated by these 
considerations and by the availability of large electronic health record (EHR) repositories, we address the problem of 
learning optimal treatment policies using EHRs. We formulate suitable objective functions that encode causal reasoning 
for reinforcement learning (RL), and present two novel algorithms for learning optimal treatment policies using 
interventional and counterfactual reasoning. Experimental results show that our RL algorithms can converge to optimal 
policies, while conventional RL methods either do not converge, or converge to suboptimal policies.