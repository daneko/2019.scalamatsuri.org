---
name: Shinichi Morimoto
title: "Home hacking backed by Akka Cluster on Kubernetes"
length: 40
audience: Intermediate
language: Japanese
twitter: shnmorimoto
github: shnmorimoto
icon: https://avatars3.githubusercontent.com/u/1239431?s=460&v=4
organization: Fringe81 Co.,Ltd. Engineer
tags:
  - Tools
  - Best Practices
  - Software Design and Architecture
suggestions:
  - Those who are interested in Akka Clusters
  - Those who are interested in running Akka on Kubernetes
contributes:
  - 
speaker_experience:
  - <a href="https://speakerdeck.com/shnmorimoto/circekaraxue-bu-genericprogrammingru-men-scalaguan-xi-summit-2018">Scala Kansai Summit 2018</a>
  - <a href="https://speakerdeck.com/shnmorimoto/real-world-kubernetes">Container X mas Party with flexy</a>
---
Recently, there have been many case studies about running online services using Kubernetes in production.
On the other hand, others are using Raspberry Pi as a way of building Kubernetes clusters at home.

I have tried my hand at a home-improvement project using a Kubernetes cluster with Raspberry Pi, but using Akka Cluster to make it reactive.

Through this project, I've realized how Kubernetes and Akka Cluster, which builds a distributed system using AKka, complement each other and build a fault-tolerant system.

In this talk, I will illustrate the benefits and lessons learned from building and operating an Akka Cluster on top of the Kubernetes architecture.
