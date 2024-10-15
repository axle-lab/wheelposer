# WheelPoser: Sparse-IMU Based Body Pose Estimation for Wheelchair Users

Open-source code, model, and dataset for our ASSETS 2024 paper "WheelPoser: Sparse-IMU Based Body Pose Estimation for Wheelchair Users"
[[DOI]](https://doi.org/10.1145/3663548.3675638) [[arXiv]](https://arxiv.org/abs/2409.08494)


![Teaser Image](./media/WheelPoser.png)

## Installation

### Python Environment and Dependencies
This code was developed in `python 3.7.12`. For dependencies, please install the latest `pytorch chumpy vctoolkit open3d pybullet qpsolvers cvxopt pytorch-lightning`.

*Installing `pytorch` with CUDA is highly recommended.

If you want to use the physics optimization module, please also compile and install [rbdl](https://github.com/rbdl/rbdl) with python bindings and the urdf reader addon enabled.

## Data Preprocessing
run 1.0 and 1.1


Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg