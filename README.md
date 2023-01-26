# Camera Calibration (OpenCV Example)

## Goal

In this section, we will learn about

- types of distortion caused by cameras
- how to find the intrinsic and extrinsic properties of a camera
- how to undistort images based off these properties

## Basics

Some pinhole cameras introduce significant distortion to images. Two major kinds of distortion are radial distortion and tangential distortion.

Radial distortion causes straight lines to appear curved. Radial distortion becomes larger the farther points are from the center of the image. For example, one image is shown below in which two edges of a chess board are marked with red lines. But, you can see that the border of the chess board is not a straight line and doesn't match with the red line. All the expected straight lines are bulged out. Visit Distortion (optics) for more details.
