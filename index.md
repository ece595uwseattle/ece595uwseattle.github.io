---
layout: index
title: "ECE 595"
description: "UW Course: Foundations of Blockchain Systems"
---
{% include JB/setup %}

## Course Information

In the big data era, the digital commons (and associated data and control) are increasingly controlled by a small number of platforms that intermediate digital interactions (eg: a majority of the top companies are digital platforms: Amazon, Apple, Google, Microsoft, Alibaba, Tencent, Facebook, Uber, Ebay). Blockchains are an emerging paradigm for permissionless distributed computing, that can remove the intermediary while at the same time providing trusted computing and storage guarantees. While applications of blockchains beyond cryptocurrencies into generalized digital platforms, are still in their infancy, blockchain technology is expected to create several trillion dollars of value in the next few years, potentially aiding the democratization of trust, data and control in digital platforms. 
In this course, we will take a first-principles, full-stack approach to blockchains: we view  blockchains as a whole integrated system involving networking, distributed consensus, data storage, incentives, and applications. We will explore the foundations of how each of these layers are designed (these foundational design principles as well as specific algorithms are the subject of cutting-edge research).  A central feature of these blockchain protocols is to tolerate adversarial users as well as rational users. While much pioneering work has happened in distributed computing on tolerating adversaries, it has focused on the permissioned setting, where there is a permission authority that decides which nodes participate in the protocol. We will focus this course on the permissionless setting without a central permissioning authority. Proving security results in this setting involves understanding convergence of certain random processes on trees (including branching random walks) under adversarial actions. Random processes plays a central role in the understanding of blockchains. 
The course will cover cutting-edge material on how ideas from a variety of theoretical areas play a pivotal role in designing these systems successfully, including distributed computing, information theory, queuing theory, networking, coding theory and game theory. For the systems-oriented students, there will be opportunities to build on a RUST codebase (built on C++) for high-performance blockchain. 


## Background for the course
The course will be broadly accessible and will only assume mathematical maturity, in particular, a background in probability theory. NO prior background in cryptography, distributed computing, or networking will be assumed. The course will be light on cryptography, introducing primitives at a black-box level.


## Expected Outcome
- Students at the end of the course will be able to bring ideas from their own fields (like distributed systems, networking, stochastic processes, game theory)     to apply to blockchain.
- Students will be able to contribute both in the academic research as well as to the industrial development of blockchain technology. 


## Who will benefit from the course? 

 This course is designed to cater to students from two different backgrounds:
- Students from computing systems background (distributed systems, communication systems, networks, machine learning systems) that want to learn the emerging       paradigm of permissionless systems.
- Students interested in the mathematical areas of stochastic processes, information theory, cryptography, coding theory, queueing theory, and game theory. The     course will cover how these mathematical tools come together to solve important problems in the exciting application area of blockchains.


## Logistics
- Time: Tue/Th 11:30am - 12:50pm
- Place: Mueller Hall 153
  - We will be using CSE 305 for some of the guest lectures, checkout the [schedule](schedule) for details
- ***Slack***: Join [https://uw-cse.slack.com](https://uw-cse.slack.com) dlsys channel for course discussions and announcements

## Prerequisites
- Proficiency in Python, familar in C/C++
  - We will mainly be using python for case study the existing systems,
    and C/C++ for some of the background hacking.
- Basic knowledge of machine learning (e.g CSE 546)
- Prior knowledge in system (operating system/database) is useful but not required.

## Homeworks and Grading

We will have assignments and a final project.

- Course project: 60%
- Homeworks: 30%
- Discussion participation: 10%

## Acknowledgement
This course is created with help from DLsys seminar group at University of Washington.
