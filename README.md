# Supplementary Videos

This repository provides four supplementary videos for the manuscript:

**Factor-Graph-Based State Estimation for Continuum Robots under Sparse Pose Measurements**

The videos show the reconstructed shapes of the continuum robot using different state estimation methods under sparse pose measurements. Three videos correspond to simulations, and one video corresponds to experiments. Each video includes results using one pose measurement and two pose measurements, together with comparisons with benchmark methods.

## Benchmark methods used in the videos

The videos compare the following methods:

- GT (Ground Truth): Reference robot shapes.

- S(Lilge2022): Spatial state estimator [1].

- S(Lilge2025): Spatial state estimator for Multirobot Systems [2].

- S+T: Spatiotemporal state estimator [3].

- S+A: Spatial estimator incorporating control inputs [4].

- Proposed: The proposed method.

In the simulation videos, all five estimation methods are evaluated compared with the ground truth; In the experimental video, S+A is excluded because it requires tendon-tension measurements, which are unavailable on our experimental platform. The remaining four estimation methods are compared under both measurement configurations.

## Video 1: Simulation trajectory Tr1





https://github.com/user-attachments/assets/45f474ae-1116-4263-9d12-b5183f2af528





## Video 2: Simulation trajectory Tr2




https://github.com/user-attachments/assets/f51e3496-8645-4842-bab9-74e1d7469d27




## Video 3: Simulation trajectory Tr3





https://github.com/user-attachments/assets/f0a7e9f3-dfb2-41d2-aa1d-c467aafa1ba4





## Video 4: Experimental trajectory / Continuous trajectory






https://github.com/user-attachments/assets/6ae73ec1-f3f0-4670-ab73-c3cfe41164cd






## References

[1] S. Lilge, T. D. Barfoot, and J. Burgner-Kahrs, "Continuum Robot State Estimation Using Gaussian Process Regression on SE(3)," *The International Journal of Robotics Research*, vol. 41, nos. 13–14, pp. 1099–1120, 2022. https://doi.org/10.1177/02783649221128843

[2] S. Lilge, T. Barfoot, and J. Burgner-Kahrs, "State Estimation for Continuum Multirobot Systems on SE(3)," *IEEE Transactions on Robotics*, vol. 41, pp. 905–925, 2025. https://doi.org/10.1109/TRO.2024.3521859

[3] S. Teetaert, S. Lilge, J. Burgner-Kahrs, and T. D. Barfoot, "A Stochastic Framework for Continuous-Time State Estimation of Continuum Robots," *arXiv preprint*, 2025.

[4] S. Lilge and T. D. Barfoot, "Incorporating Control Inputs in Continuous-Time Gaussian Process State Estimation for Robotics," *Robotica*, vol. 43, no. 3, pp. 1067–1086, 2025. https://doi.org/10.1017/S0263574725000116
