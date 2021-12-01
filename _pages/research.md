---
layout: archive
title: "Research"
excerpt: "Research"
author_profile: true
redirect_from:
  - /research
---


### **1) PAL - Pretext Based Active Learning [[project-page]](https://www.bmvc2021-virtualconference.com/conference/papers/paper_1061.html)[[slides]](https://shubhangb97.github.io/files/PAL_BMVC_slides.pdf) BMVC ’21**<br>*Master’s Thesis, Advisor -[Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/), IIT Bombay* <br>
**Introduction**- Labelling data for deep learning is expensive, and active learning helps minimize that cost by choosing a
subset of most informative unlabeled images for labelling. Most current active learning approaches rely overly on task
based uncertainty, which is error prone or use diversity as a metric which is susceptible to dimensionality. We propose using
self supervision to address these issues. <br>
- Proposed a novel technique to predict informativeness of a sample combining supervision and self supervision using a
novel function for better reliability and robustness, using the difficulty of solving the pretext task as an input
- Introduced diversity using a self supervised sub-querying strategy, mitigating dimensionality related disadvantages
- Outperformed current State of the Art Active learning techniques in a variety of experiments including noisy
labeling scenarios on multiple datasets including CIFAR10, Cityscapes, SVHN and Caltech-101, setting new benchmarks

### **2)Robust Cross Validation in Compressed Sensing [[paper]](https://shubhangb97.github.io/files/RobustCross_Validation_paper_ICASSP.pdf) [[supplement]](https://shubhangb97.github.io/files/RobustCross_Validation_supplement_ICASSP.pdf) EUSIPCO ’21** <br>*Advisor - [Prof. Ajit Rajwade](https://www.cse.iitb.ac.in/~ajitvr/), IIT Bombay* <br>
**Introduction**- Compressive reconstruction algorithms require careful selection of parameters for optimal performance. We
study the use of cross validation for tuning these parameters and providing probabilistic quality assurance for the recovered
signal in absence of information about noise level and signal sparsity.
- Proposed a novel technique for selecting parameters using the L1 CV error and theoretically proved that it’s use
yields optimal reconstruction with high probability in presence of mixed gaussian and impulsive noise
- Derived novel bound on the Compressed Sensing(CS) recovery error estimate in terms of the L1 Cross Validation(CV)
error which is robust to impulsive and gaussian noise
- Conducted extensive simulations, demonstrating that the L1 CV based strategy yields a more than order of magnitude
gain in PSNR over traditional L2 CV based methods in presence of mixed gaussian and impulsive noise

### **3)CCNet : Explainable CNN’s through clustering**  <br> *Advisor- [Prof. Narendra Ahuja](https://ece.illinois.edu/about/directory/faculty/n-ahuja), UIUC*<br>
**Introduction**- Convolutional Neural networks, despite all their success represent a black box, with very little information available about their decision and confidence metrics. We work to make the decisions made by CNN's more explainable by replacing the opaque fully connected (FC) layers with a clustering algorithm (CA) modelling the probability density function of a class in an embedding space.
- Proposed novel CA (clustering algorithm) which is used to train convolutional layers without using fully connected layers helping better interpretability (OOD, error awareness).
- Use of CA in place of FC layers helps reduce network size by upto 90 % without a loss in performance, with results demonstrated on ImageNet, CIFAR-10 and CIFAR-100.


### **4)Real Time Wireless Video Transmission Through Obstacles [[report]](https://shubhangb97.github.io/files/EDL_Report.pdf)**<br> *Advisor- [Prof. Shalabh Gupta](https://www.ee.iitb.ac.in/wiki/faculty/shalabh), IIT Bombay*<br>
**Introduction**- Transmitting video in real time through obstacles like buildings using portable transmitters and receivers is
a difficult, but important task. We try to develop a small, efficient system for solving this problem.

- Designed, simulated, soldered and tested PAL video transmitter and receiver modules at 400 MHz for real time exchange
of video achieving a range of more than 100 m out of line of sight
- Designed upconverter, downcoverter, noise rejection filter and amplifiers for increasing range of the system
- Designed system capable of robustly sending and receiving video

### **5)Noise Tolerant QR Code Recognizer using Hopfield Network [[pre-print]](https://shubhangb97.github.io/files/QR_code_1.pdf)** <br> *Advisor - [Prof. Suyash Awate](https://www.cse.iitb.ac.in/~suyash/), IIT Bombay*<br>
**Introduction**- Hopfield networks are a type of recurrent neural networks used for noise tolerant associative memory, but
are limited by their low memory capacity. We study their use for Robust QR code recognition.

- Implemented a Hopfield network in MATLAB and trained it using the Pseudo-Inverse rule for QR code denoising
- Proposed a novel technique to use Hopfield networks in parallel using the energy gradient difference around trained
and false energy minima, providing a method to deal with applications requiring large storage capacity
- Expanded capacity of Hopfield network QR code recognition by an order of magnitude using proposed technique

### **6)Self Supervision for COVID-19 Detection** <br> *Advisor - [Prof. Amit Sethi](https://www.ee.iitb.ac.in/~asethi/), IIT Bombay* <br>
 **Introduction**- X-Rays were a promising and more accessible alternative for detecting COVID-19. There was a shortage of
annotated images for its diagnosis. We explore using Self supervision to mitigate this problem.
- Explored literature on use of Self supervision for deep learning on medical images and in computer vision
- Achieved over 90% accuracy on the COVID-Net dataset using a state of the art contrastive self supervision method on
the CheXpert dataset with 200,000+ chest X rays, comparing favourably to ImageNet based initialization for our task.

### **7)Designing Efficient Network Caching Algorithms** <br> *Advisor - [Prof. Prasanna Chaporkar](https://www.ee.iitb.ac.in/wiki/faculty/chaporkar), IIT Bombay*<br>
**Introduction**- Most network caching algorithms are built on the premise that file popularity distributions remain static.
Recent studies indicate this assumption is not accurate in the real world. We study caching algorithms considering a more
realistic changing distribution model.
- Reviewed literature on performance of caching techniques including LRU, m-LRU, LRU(m) in real world scenarios
- Proposed a new adaptive algorithm based on LRU(m) to maximize cache hit probability by exploiting trade off
between rate of learning current file distribution and accuracy of learning current file distribution
