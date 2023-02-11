---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

Living in a complex and dynamic world, we perceive a lot of visual information all the time and integrate them to form our own perception, memory and understanding of this complex and dynamic world. Even though the input information is 2D and changes in the retina, we still have the ability to steadily perceive the world, understand the world and achieve our goals. 

My research is to combine human psychophysics, eye-tracking, neuroimaging (fMRI & EEG), computational methods (linear-regression, MVPA, RSA, IEM and pRF) and deep learning models (CNN, GAN and VAE) to better understand both behavioral and neural mechanisms of visual processing.
Below are the two main topics I am interested in with several subtopics and projects I am working on: 

### Neural and behavioral meachnisms of visual perception  
> Object-location binding across saccades  
- Increasing studies have found interactions between object identity adn spatial location. Even when location is irrelevatn to the task, location can be bound to object representations. However, what's the reference framework of object-location binding? Is it retinotopic (gaze-centered) or spatiotopic (world-centered)? I investigate the dynamic framework of object-location binding across eye movements using the Spatial Congruency Bias paradigm from three perspectives: (1) Observer's eye-movements: how dynamic saccade context (using multiple saccades) influences object-location binding. (2) External environment: how the landmark influences object-location binding. (3) Object's movements: how object-location binding happens of a moving object.  

> Depth perception and 3D integration  
- Visual input is initially recorded in 2D on our retinas, however, we can know the location of an object in 3D spatial coordinates quickly. Thus, our brains can automaticaly integrate 2D representations with various depth cues to achieve 3D perception. I investigate human depth perception in two ways: (1) Depth representations of an object in an image: to explore the brain representations of relatice and absolute depth of the object in an image using EEG and computational approaches. (2) Spatiotemporal representations of 3D perception: to unfold the spatiotemporal neural mechanisms of depth perception and 3D integration using a fMRI-EEG fusion computational framework.  

> Generally spatial representation  
- As we move our eyes around the world, we are able to integrate visual input and achieve a stable visual percept across eye movements. However, previous studies have found that our visual system, from primary visual cortex to higher level visual regions, represents object locations in natively reitnotopic (gaze-centered) but not spatiotopic (gaze-independent) coordinates. How can our brain form a stable spatial representation of objects? Is spatiotopic information represented elsewhere in the brain, or might we trigger spatiotopic representations in visual areas by some other factors (e.g., dynamic saccades, landmarks, etc.)  

### Artificial neural networks in cognitive computational neuroscience  
> Inter-individual neural converters  
- Most models in cognitive and computational neuroscience trained on one subject don’t generalize to other subjects due to individual differences. An ideal individual-to-individual neural converter is expected to generate real neural signals of one subject from those of another one, which can overcome the problem of individual differences for cognitive and computational models. I am working on proposing novel inter-individual EEG and fMRI converter which can realize a flexible and high-performance mapping from invidual to indivual and provide insights for both neural engineering and cognitive neuroscience.  

> Brain encoding and decoding  
- The most intuitive and direct way to understand the relationship between visual input from the world and neural computing in our brains is to get through from visual inputs to neural latent space to brain activity and from brain activity to visual latent space to visual inputs. I aim to construct both image-to-brain encoding (signal generation) and brain-to-image decoding (image reconstruction) models to better understand visual perception.

> Reverser engineering to interpret neural mechanisms  
- In recent years, artificial neural networs (ANNs) can achieve human-level performance in object and face recognition task. I am also trying to apply hypothesis-based reverse engineering to provide a novel way to interpret neural mechanims of object and face perception. We can manipulate ANN activations based on different hypotheses and compare the modified representations with human brain representations to make inference for the neural mechanisms underlying human behaviors.