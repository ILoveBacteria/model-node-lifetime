# Model Node Lifetime

[![Last commit](https://img.shields.io/github/last-commit/ILoveBacteria/model-node-lifetime)](https://github.com/ILoveBacteria/model-node-lifetime/commits/master)

## Description

Instructor: Dr.Safaie

In this programming exercise, we will explore the **reliability** of systems in the form of stations. Each system component is a Bernoulli random variable that can only be in two states: operational or not operational. We will examine situations where each system component has a certain **lifespan**. With this study, we can calculate the reliability of different systems at any moment as a function of time. We will dynamically analyze the reliability and resilience of the system by studying the probability of incompatibility, the probability of being isolated, and the lifetime of a single user. 

The user failure model is based on their lifetime, a non-negative random variable from a certain probability distribution. We will define two-lifetime distributions: **NWUE** and **NBUE**. We will investigate which one of these features will make the system stronger. The lifetime distribution, user behavior, and service duration show the time of being online in the network. In this way, we can study stochastic systems. 

The proposed model is called a **passive** model. It assumes that the link or communication between the users is defective, and will never be repaired. The user will remain in the network until all of their neighbors or a percentage of their neighbors go offline. As soon as such an event occurs, the user leaves the network. For this reason, we assume that the users who entered the network and formed the system have a random lifetime that follows a certain probability distribution. This passive model is suitable for scenarios where a link in the network is deleted or damaged, and the time to repair it is much longer than the lifetime of the user.
