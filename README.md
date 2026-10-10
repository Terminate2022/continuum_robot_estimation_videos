# Supplementary Videos

This repository provides four supplementary videos for the manuscript:

**Factor-Graph-Based State Estimation for Continuum Robots under Sparse Pose Measurements**

The videos show the reconstructed shapes of the continuum robot using different state estimation methods under sparse pose measurements. Three videos correspond to simulations, and one video corresponds to experiments. Each video includes results using one pose measurement and two pose measurements, together with comparisons with benchmark methods.

## Benchmark methods used in the videos

The videos compare the following methods:

- GT (Ground Truth): Reference robot shapes.

- S(Lilge2022): Spatial Gaussian process estimator on SE(3), based on Lilge et al. [1].

- S(Lilge2025): Spatial state estimator based on Lilge et al. [2].

- S+T: Spatiotemporal state estimator based on Teetaert et al. [3].

- S+A: Spatial estimator incorporating tendon-actuation information.

- Proposed: The proposed method.

In the simulation videos, all five estimation methods are evaluated compared with the ground truth; In the experimental video, S+A is excluded because it requires tendon-tension measurements, which are unavailable on our experimental platform. The remaining four estimation methods are compared under both measurement configurations.

## Video 1: Simulation trajectory S1
https://github.com/user-attachments/assets/2bb9571e-3062-476f-833a-9a8f8e3dfbfe
## Video 2: Simulation trajectory S2
https://github.com/user-attachments/assets/3e9b98cb-3b37-4be7-a02d-578cf26abbf6
## Video 3: Simulation trajectory C1
https://github.com/user-attachments/assets/ec825da4-a12c-45f1-b241-cee95a5ebe2c
## Video 4: Experimental trajectory
https://github.com/user-attachments/assets/83481d3b-3737-41c2-ab93-3783cc631c44
## References

[1] S. Lilge, T. D. Barfoot, and J. Burgner-Kahrs, "Continuum Robot State Estimation Using Gaussian Process Regression on SE(3)," *The International Journal of Robotics Research*, vol. 41, nos. 13–14, pp. 1099–1120, 2022. https://doi.org/10.1177/02783649221128843

[2] S. Lilge, T. Barfoot, and J. Burgner-Kahrs, "State Estimation for Continuum Multirobot Systems on SE(3)," *IEEE Transactions on Robotics*, vol. 41, pp. 905–925, 2025. https://doi.org/10.1109/TRO.2024.3521859

[3] S. Teetaert, S. Lilge, J. Burgner-Kahrs, and T. D. Barfoot, "A Stochastic Framework for Continuous-Time State Estimation of Continuum Robots," *arXiv preprint*, 2025.

[4] S. Lilge and T. D. Barfoot, "Incorporating Control Inputs in Continuous-Time Gaussian Process State Estimation for Robotics," *Robotica*, vol. 43, no. 3, pp. 1067–1086, 2025. https://doi.org/10.1017/S0263574725000116
