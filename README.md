# Multiview Camera Calibration for Ground Plane Estimation

The camera calibration pipeline involves the computation of camera intrinsics and extrinsics. The user provides as input checkerboard footage from each camera and multiple-view footage, including data from an omnidirectional camera. OpenCV is used to calculate the camera intrinsics. For extrinsics calibration, OpenSfM is utilised. The resulting extrinsics are adjusted and aligned by employing a user-selected set of 4–10 ground points in each view. These points are also used to determine a region of interest, enabling the adjustment, scaling, and rotation of the ground plane projection. This process ensures that the projection focuses accurately on the desired area.
 
### Environment Setup

Environment setup is described in [setup.md](docs/setup.md).


### Calibration
A step by step guide to calibrating the cameras is described in [calibration.md](docs/calibration.md).
