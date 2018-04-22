# GAN-Regret-Minimization
A regret minimization approach to training Generative Adversarial Networks (GANs). This was my project in the "Algorithms and Optimization for Big Data" course.

Training Generative Adversarial Networks (GANs) has been a major research problem ever since its inception. The motivation for this project was to devise a method which can accelerate the convergence rate of GANs. The general human approach is to minimize the regret in life by learning from the past. This regret minimization approach, has been well established in the domain of game theory. We know that in GANs, the generator and discriminator are involved in a minimax game. So, it made sense to try this approach in the training of GANs.

The regret minimization approach splits into 2 implementations: global regret and local regret. Since, global regret is computationally intractable, so the local regret approach was finalized. The general setting for a game is described as follows:
