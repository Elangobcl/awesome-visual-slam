# The list of vision-based SLAM / Visual Odometry open source, blogs, and papers

## Useful third party libraries
###### Basic vision and trasformation libraries
- [OpenCV](http://opencv.org/)
- [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page)
- [Sophus](https://github.com/strasdat/Sophus)
- [ROS](http://www.ros.org/)
- [PointCloud](http://pointclouds.org/)

###### Loop detection
- [dorian3d](https://github.com/dorian3d)

###### Graph Optimization
- [ceres-solver](https://github.com/ceres-solver/ceres-solver)
- [g2o](https://github.com/RainerKuemmerle/g2o)
- [gtasm](https://collab.cc.gatech.edu/borg/gtsam?destination=node%2F299)
- [Vertigo](http://openslam.org/vertigo.html)

###### Map library
- [ETHZ ASL/Grip Map](https://github.com/ethz-asl/grid_map)
- [OmniMapper](https://github.com/CognitiveRobotics/omnimapper/wiki)
- [OctoMap](https://github.com/OctoMap/octomap)

### Experient/Benchmark/Test dataset
- [TUM Universtiy](http://vision.in.tum.de/data/datasets/rgbd-dataset/download)
- [KTTI Vision benchmark](http://www.cvlibs.net/datasets/kitti/eval_odometry.php)

### Nice Repositories

###### Tools
- [rgbd-datasest tool from TUM](https://vision.in.tum.de/data/datasets/rgbd-dataset/tools)

###### RGB (Monocular):

- [LSD-SLAM](https://github.com/tum-vision/lsd_slam). Available on ROS
>LSD-SLAM: Large-Scale Direct Monocular SLAM, J. Engel, T. Schöps, D. Cremers, ECCV '14
>Semi-Dense Visual Odometry for a Monocular Camera, J. Engel, J. Sturm, D. Cremers, ICCV '13

- [ORB-SLAM](https://github.com/raulmur/ORB_SLAM). Available on ROS : Yes
> [1] Raúl Mur-Artal, J. M. M. Montiel and Juan D. Tardós. ORB-SLAM: A Versatile and Accurate Monocular SLAM System. IEEE > Transactions on Robotics, vol. 31, no. 5, pp. 1147-1163, 2015. (2015 IEEE Transactions on Robotics Best Paper Award). PDF.
> [2] Dorian Gálvez-López and Juan D. Tardós. Bags of Binary Words for Fast Place Recognition in Image Sequences. IEEE > Transactions on Robotics, vol. 28, no. 5, pp. 1188-1197, 2012. PDF.

- [Nister's Five Point Algorithm for Essential Matrix estimation, and FAST features, with a KLT tracker](https://github.com/avisingh599/mono-vo)
>D. Nister, “An efficient solution to the five-point relative pose problem,” Pattern Analysis and Machine Intelligence, IEEE Transactions on, vol. 26, no. 6, pp. 756–770, 2004.

###### RGB and Depth:
- [OpenCV RGBD-Odometry (Visual Odometry based RGB-D images)](https://github.com/tzutalin/OpenCV-RgbdOdometry)
>Real-Time Visual Odometry from Dense RGB-D Images, F. Steinbucker, J. Strum, D. Cremers, ICCV, 2011

- [Dense Visual SLAM for RGB-D Cameras](https://github.com/tum-vision/dvo_slam). Available on ROS
>[1]Dense Visual SLAM for RGB-D Cameras (C. Kerl, J. Sturm, D. Cremers), In Proc. of the Int. Conf. on Intelligent Robot Systems (IROS), 2013.
[2]Robust Odometry Estimation for RGB-D Cameras (C. Kerl, J. Sturm, D. Cremers), In Proc. of the IEEE Int. Conf. on Robotics and Automation (ICRA), 2013
[3]Real-Time Visual Odometry from Dense RGB-D Images (F. Steinbruecker, J. Sturm, D. Cremers), In Workshop on Live Dense Reconstruction with Moving Cameras at the Intl. Conf. on Computer Vision (ICCV), 2011.


- [RTAB MAP - Real-Time Appearance-Based Mapping](https://github.com/introlab/rtabmap). Available on ROS
> Online Global Loop Closure Detection for Large-Scale Multi-Session Graph-Based SLAM, 2014
> Appearance-Based Loop Closure Detection for Online Large-Scale and Long-Term Operation, 2013

- [ORB2-SLAM](https://github.com/raulmur/ORB_SLAM2).
> [1] Raúl Mur-Artal, J. M. M. Montiel and Juan D. Tardós. ORB-SLAM: A Versatile and Accurate Monocular SLAM System. IEEE > Transactions on Robotics, vol. 31, no. 5, pp. 1147-1163, 2015. (2015 IEEE Transactions on Robotics Best Paper Award).
> [2] Dorian Gálvez-López and Juan D. Tardós. Bags of Binary Words for Fast Place Recognition in Image Sequences. IEEE Transactions on Robotics, vol. 28, no. 5, pp. 1188-1197, 2012.
