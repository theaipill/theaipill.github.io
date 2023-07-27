---
layout: archive
title: "Patents & Publications"
permalink: /publications/
author_profile: true
classes: wide
---

### [Google Scholar Link](https://scholar.google.com/citations?user=64ngaD4AAAAJ&hl=en), h-index:9


---
Patents _(multi-national, worldwide applications)_
---

* [US20230086009A1](https://patents.google.com/patent/US20230086009A1), [WO2023049339A1](https://patents.google.com/patent/WO2023049339A1) System and techniques to normalize objects in spatial imaging of spaces
* [US10970561B2](https://patents.google.com/patent/US10970561B2) Detecting roadway objects in real-time images
* [US10586118B2](https://patents.google.com/patent/US10586118B2) Localizing traffic situation using multi-vehicle collaboration
* [JP6729673B2](https://patents.google.com/patent/JP6729673B2) Location of traffic event by cooperation of multiple vehicles
* [US10395530B2](https://patents.google.com/patent/US10395530B2) Situational understanding of unknown roadway conditions that are ahead for a connected vehicle
* [US10043084B2](https://patents.google.com/patent/US10043084B2) Hierarchical context-aware extremity detection
* [JP6394735B2](https://patents.google.com/patent/JP6394735B2) Detection of limbs using hierarchical context-aware
* [US9805276B2](https://patents.google.com/patent/US9805276B2) Generating real-time driver familiarity index for fine-grained dynamic road scenes
* [JP6341311B2](https://patents.google.com/patent/JP6341311B2) Real-time creation of familiarity index for driver's dynamic road scene
* [US9792821B1](https://patents.google.com/patent/US9792821B1) Understanding road scene situation and semantic representation of road scene situation for reliable sharing
* [JP6414255B](https://patents.google.com/patent/JP6414255B2) Semantic representation of road scene situations for understanding and sharing of road scene situations
* [US9129161B2](https://patents.google.com/patent/US9129161B2) Computationally efficient scene classification
* [JP6299427B2](https://patents.google.com/patent/JP6299427B2) Scene estimation method and scene estimation apparatus
* [US10970561B2](https://patents.google.com/patent/US10970561B2) Detecting roadway objects in real-time images
* [US20160207458A1](https://patents.google.com/patent/US20160207458A1) Real time driving difficulty categorization


---
Publications
---

* [Classification of executed and imagined motor movement EEG signals](https://www.semanticscholar.org/paper/Classification-of-Executed-and-Imagined-Motor-EEG-Sleight-Pillai/8a9d0ee78265cee260f1072f81f7819e0f752519), @inproceedings{Sleight2009ClassificationOE,
  title={Classification of Executed and Imagined Motor Movement EEG Signals},
  author={Jason Sleight and Preeti J. Pillai and S. Mohan},
  year={2009},
  url={https://api.semanticscholar.org/CorpusID:7434878}
}

Electroencephalography (EEG), which contains cortical potentials during various mental processes, can be used to provide neural input signals to activate a brain machine interface (BMI). The effectiveness of such an EEG-based prosthetic system would rely on correct classification of executed motor signals from imagined motor movement signals; an executed motor signal should initiate movement in the artificial limb while signals from motor imagery should be filtered out. This work evaluates the performance of features based on average EEG signal power contained in different frequency bands in order to distinguish between the executed and imagined EEG signals. We also investigate Independent Component Analysis (ICA) as a scheme to remove irrelevant artifacts from the EEG signals. Results demonstrate that using EEG for classification can be performed effectively; however results vary significantly from patient to patient, suggesting that BMI must highly specialized for an individual patient.



* [Hierarchical context-aware hand detection algorithm for naturalistic driving](https://ieeexplore.ieee.org/document/7795723) 2016 IEEE 19th International Conference on Intelligent Transportation Systems (ITSC), Rio de Janeiro, Brazil, 2016, pp. 1291-1297, doi: 10.1109/ITSC.2016.7795723

  
  Hand activity is a critical monitoring component in understanding a driver's behavior within the car. Current vision-based hand detection algorithms perform poorly in naturalistic settings, due to various challenges such as global illumination changes and constant hand deformation and occlusion. To achieve a more accurate and robust hand detection system, this paper presents a hierarchical context-aware hand detection algorithm, which explicitly explores context cues in the vehicle such as prevalent hand shapes and locations, preferred driving habit and coupling effect between multiple hands. The proposed context-aware hand detection algorithm significantly outperforms the state-of-the-art on the VIVA hand dataset.


* [CHASE Algorithm: "Ease of Driving" Classification](https://ieeexplore.ieee.org/abstract/document/7313203)2015 IEEE 18th International Conference on Intelligent Transportation Systems, Gran Canaria, Spain, 2015, pp. 644-649, doi: 10.1109/ITSC.2015.111

  
  In this paper, we present the concept of "Ease of Driving" or EoD rating for road scene environment. We introduce the Classification by Holistic Analysis of Scene Environment (CHASE) algorithm to automatically classify the EoD rating using computer vision and machine learning techniques. With the CHASE algorithm we were able to achieve an accuracy of 86.84 % to classify the EoD. In the near future, EoD information will be used to create better navigation services to improve the driving comfort and mobility by leveraging the existing camera sensors in the car.
 
* [“Ease of Driving” Road Classification for Night-time Driving Conditions](https://www.sae.org/publications/technical-papers/content/2016-01-0119/) SAE World Congress and Exhibition 2016-01-0119, 2016, https://doi.org/10.4271/2016-01-0119

This paper is an extension of our previous work on the CHASE (Classification by Holistic Analysis of Scene Environment) algorithm, that automatically classifies the driving complexity of a road scene image during day-time conditions and assigns it an ‘Ease of Driving’ (EoD) score. At night, apart from traffic variations and road type conditions, illumination changes are a major predominant factor that affect the road visibility and the driving easiness. In order to resolve the problem of analyzing the driving complexity of roads at night, a brightness detection module is incorporated in our end-to-end nighttime EoD system, which computes the ‘brightness factor’ (bright or dark) for that given night-time road scene. The brightness factor along with a multi-level machine learning classifier is then used to classify the EoD score for a night-time road scene. Our end-to-end ‘Night-time EoD system’ is a real-time onboard system implemented and tested on road scene data collected in Japan. We have improved the scope of the CHASE algorithm for computing EoD score for night-time driving conditions by including a brightness detection module.

* [A Lightweight Inference Method for Image Classification.](https://dl.acm.org/doi/10.5555/3020285.3020294), AW'13: Proceedings of the 2013 UAI Conference on Application Workshops: Big Data meet Complex Models and Models for Spatial, Temporal and Network Data - Volume 10, 24July 2013, Pages 50–57

We demonstrate a two phase classification method, first of individual pixels,
then of fixed regions of pixels for scene
classification—the task of assigning posteriors that characterize an entire image. This
can be realized with a probabilistic graphical
model (PGM), without the characteristic segmentation and aggregation tasks characteristic of visual object recognition. Instead the
spatial aspects of the reasoning task are determined separately by a segmented partition
of the image that is fixed before feature extraction. The partition generates histograms
of pixel classifications treated as virtual evidence to the PGM. We implement a sampling
method to learn the PGM using virtual evidence. Tests on a provisional dataset show
good (+70%) classification accuracy among
most all classes.
