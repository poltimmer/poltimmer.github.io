+++
draft = false
title = 'Simulating Snow Crystal Growth with Neural Networks'
+++

Snow crystal growth is a highly complex and nonlinear process, and therefore it is difficult to simulate. A lot of research has been done on the topic simulating snow crystal growth with computationally expensive numerical models. For my research, I thought it would be interesting to use machine learning to emulate and accelerate these simulations. No previous research has been done on simulating snow crystal growth with neural networks, and due to the nonlinearity of the system and its probabilistic nature, this is a very challenging problem. Existing methods for neural simulation of dynamical systems fail to address some of the challenges of snow crystal growth, and fall short of producing accurate and diverse simulations.

In my research, I developed the Crystal Growth Neural Emulator (CGNE), a tailored neural network model for simulating crystallization processes at the mesoscopic scale. I show this model to be able to produce accurate and diverse simulations of snow crystal growth, while accelerating the simulation process over numerical models. You can read the full research in my [thesis](/pdf/thesis_pol_timmer.pdf), or alternatively, you can read a short summary of the research in the [paper](https://openreview.net/pdf?id=ZdaZoiYeG7) I published in D3S3, a NeurIPS 2024 workshop.

The code for the project is available on [GitHub](https://github.com/poltimmer/CGNE). This includes the code for the neural network model, as well as the code used to generate the dataset.

