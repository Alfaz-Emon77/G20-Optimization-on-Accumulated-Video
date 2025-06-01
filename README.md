# G20-Optimization-on-Accumulated-Video
Human KeyPoint Localization and Optimization using G2O


---


This repository contains the implementation of **G2O-based keypoint optimization** on occluded videos. The project focuses on improving keypoint localization accuracy by leveraging graph-based optimization techniques, specifically the [G2O](https://github.com/RainerKuemmerle/g2o) framework.

---

## Overview

In many computer vision applications, such as human pose estimation and SLAM, video frames often contain occluded or missing keypoints. This project applies G2O optimization to refine keypoint localization in videos where occlusions occur, enhancing overall robustness and accuracy.

---

## Features

* Keypoint detection and tracking in video frames
* Handling occluded or missing keypoints using graph optimization
* Integration with G2O library for nonlinear least squares optimization
* Visualization of optimized keypoints on occluded video sequences

---

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/g2o-optimization-occluded-video.git
   cd g2o-optimization-occluded-video
   ```

2. **Install dependencies:**

   * [G2O library](https://github.com/RainerKuemmerle/g2o) (follow instructions to build and install)
   * OpenCV (for video processing and visualization)
   * Eigen3 (for linear algebra)

3. **Build the project:**

   Use CMake to configure and build:

   ```bash
   mkdir build && cd build
   cmake ..
   make
   ```

---

## Usage

Run the optimization pipeline on your input video:

```bash
./g2o_optimization --input path/to/your/video.mp4 --output path/to/output/video.mp4
```

Command-line options:

* `--input`: Path to input occluded video file
* `--output`: Path to save the optimized output video

---

## Results

Example frames showing the improvement of keypoint localization after G2O optimization on occluded video sequences.

*Add images or GIFs here showing before/after keypoint results.*

---

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your improvements or bug fixes.

---



---

## Authors

* Shirajul Islam Shakur
* Alfaz Uddin Emon
* Mohaiminul Islam

Supervised by Mohammad Mahadi Hassan and Md. Khaliluzzaman
Department of Computer Science and Engineering
International Islamic University Chittagong

---
