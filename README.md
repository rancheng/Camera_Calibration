# Camera_Calibration
Camera Calibration code for 9*6 squared image template compatible with CLion.

This is an tutorial code from OpenCV official source repository, and do modification to optimize the output for camera intrinsic data.

### Build and Run

Camera Calibration requires [OpenCV](https://opencv.org/) v3.3+ to run.

Install the OpenCV on Ubuntu 16.04.

```sh
$ cd ~/Documents
$ wget -i https://github.com/opencv/opencv/archive/3.3.1.zip
$ tar xvzf opencv-3.3.1
$ cd opencv-3.3.1
$ mkdir build
$ cd build
$ cmake ..
$ make install
```

For Building...

```sh
$ cd ~/Documents
$ git clone https://github.com/rancheng/Camera_Calibration.git
$ cd camera_calibration
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./camera_calibration
```
