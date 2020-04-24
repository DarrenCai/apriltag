Update
====
The [aprilgrid](https://github.com/ethz-asl/kalibr/wiki/calibration-targets#olson) is used in [Kalibr](https://github.com/ethz-asl/kalibr) with [AprilTag 1](https://github.com/ethz-asl/ethzasl_apriltag2).
So I add tagGrid36h11 in [AprilTag 3](https://github.com/AprilRobotics/apriltag) in order to aprilgrid can enjoy AprilTag3's optimization.
Please open **example/aprilgrid_demo.cc** to get more information and I provide image for testing in **example/image_aprilgrid**.


Usage
====
[User Guide](https://github.com/AprilRobotics/apriltag/wiki/AprilTag-User-Guide)


If you have CMake and OpenCV installed or it is not difficult to build, then do:

    $ mkdir build
    $ cd build
    $ cmake ..
    $ make -j4
    $ ./aprilgrid_demo ../example/image_aprilgrid/aprilgrid_1.png 
    