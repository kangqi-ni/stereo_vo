# Stereo Visual Odometry on KITTI datasets

This project implements a basic stereo visual odometry on kitti datasets for learning purposes.
Its simple pipeline includes fundamental components of a working visual odometry.   

To use this code with a kitti sequence, specify the path to the kitti sequence in config/config.yaml.

config/config.yaml also contains the parameters to configure the algorithm.
Then run ./bin/run_kitti in the terminal.

Please check CMakeLists.txt for dependencies.

Visualization:
![Visualization](https://github.com/kangqi-ni/stereo_vo/blob/master/Visualizer.png)

References:

[1] Mur-Artal, R., Montiel, J. M. M. & Tardós, J. D. (2015). ORB-SLAM: a Versatile and Accurate Monocular SLAM System. CoRR, abs/1502.00956.

[2] Xiang, Gao. (2018). Slambook2. https://github.com/gaoxiang12/slambook2.
