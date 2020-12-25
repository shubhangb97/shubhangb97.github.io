---
permalink: /
title: "Research"
excerpt: "Research"
author_profile: true
redirect_from:
  - /research/
---

# **Research**
### PAL - Pretext Based Active Learning [paper] Submitted, CVPR ’21
Master’s Thesis, Advisor - Prof. Amit Sethi, IIT Bombay Mar ’20 – Present

**Introduction**- Labelling data for deep learning is expensive, and active learning helps minimise that cost by choosing a
subset of most informative unlabeled images for labelling. Most current active learning approaches rely overly on task
based uncertainty, which is error prone or use diversity as a metric which is susceptible to dimensionality. We propose using
self supervision to address these issues.

- Proposed a novel technique to predict informativeness of a sample combining supervision and self supervision using a
novel function for better reliability and robustness, using the difficulty of solving the pretext task as an input

- Introduced diversity using a self supervised sub-querying strategy, mitigating dimensionality related disadvantages

- Outperformed current State of the Art Active learning techniques in a variety of experiments including noisy
labeling scenarios on multiple datasets including CIFAR10, CIFAR100, SVHN and Caltech-101, setting new benchmarks

### **Robust Cross Validation in Compressed Sensing [paper] [supplement] Submitted, ICASSP ’21**
Advisor - Prof. Ajit Rajwade, IIT Bombay March ’20 – Oct ’20

**Introduction**- Compressive reconstruction algorithms require careful selection of parameters for optimal performance. We
study the use of cross validation for tuning these parameters and providing probabilistic quality assurance for the recovered
signal in absence of information about noise level and signal sparsity.

- Proposed a novel technique for selecting parameters using the L1 CV error and theoretically proved that it’s use
yields optimal reconstruction with high probability in presence of mixed gaussian and impulsive noise

- Derived novel bound on the Compressed Sensing(CS) recovery error estimate in terms of the L1 Cross Validation(CV)
error which is robust to impulsive and gaussian noise
- Conducted extensive simulations, demonstrating that the L1 CV based strategy yields a more than order of magnitude
gain in PSNR over traditional L2 CV based methods in presence of mixed gaussian and impulsive noise

### **Real Time Wireless Video Transmission Through Obstacles [report]**
Advisor- Prof. Shalabh Gupta, IIT Bombay Jan’19-May’19

**Introduction**- Transmitting video in real time through obstacles like buildings using portable transmitters and receivers is
a difficult, but important task. We try to develop a small, efficient system for solving this problem.

- Designed, simulated, soldered and tested PAL video transmitter and receiver modules at 400 MHz for real time exchange
of video achieving a range of more than 100 m out of line of sight
- Designed upconverter, downcoverter, noise rejection filter and amplifiers for increasing range of the system
- Submitted system capable of robustly sending and receiving video for use by Indian Armed Forces

### **Noise Tolerant QR Code Recognizer using Hopfield Network [pre-print]**
Advisor - Prof. Suyash Awate, IIT Bombay May’18-Jul’18

**Introduction**- Hopfield networks are a type of recurrent neural networks used for noise tolerant associative memory, but
are limited by their low memory capacity. We study their use for Robust QR code recognition.

- Implemented a Hopfield network in MATLAB and trained it using the Pseudo-Inverse rule for QR code denoising
- Proposed a novel technique to use Hopfield networks in parallel using the energy gradient difference around trained
and false energy minima, providing a method to deal with applications requiring large storage capacity
- Expanded capacity of Hopfield network QR code recognition by an order of magnitude using proposed technique

### **Self Supervision for COVID-19 Detection Research Project**
Advisor - Prof. Amit Sethi, IIT Bombay Feb’20-June’20

**Introduction**- X-Rays were a promising and more accessible alternative for detecting COVID-19. There was a shortage of
annotated images for its diagnosis. We explore using Self supervision to mitigate this problem.
- Explored literature on use of Self supervision for deep learning on medical images and in computer vision
- Achieved over 90% accuracy on the COVID-Net dataset using a state of the art contrastive self supervision method on
the CheXpert dataset with 200,000+ chest X rays, comparing favourably to ImageNet based initialization for our task.

### **Designing Efficient Network Caching Algorithms Research Project**
Advisor - Prof. Prasanna Chaporkar, IIT Bombay Jan’20-June’20

**Introduction**- Most network caching algorithms are built on the premise that file popularity distributions remain static.
Recent studies indicate this assumption is not accurate in the real world. We study caching algorithms considering a more
realistic changing distribution model.
- Reviewed literature on performance of caching techniques including LRU, m-LRU, LRU(m) in real world scenarios
- Proposed a new adaptive algorithm based on LRU(m) to maximize cache hit probability by exploiting trade off
between rate of learning current file distribution and accuracy of learning current file distribution
