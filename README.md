# __Simple Object Tracker__

## Overview
This project is a basic real-time computer vision application developed using Python and OpenCV. It captures live video from a Logitech C270 webcam and detects a single predominantly black object against a plain white background. The application identifies the object's boundaries, draws a rectangular bounding box around it, and displays its center coordinates (X, Y) in the image. The target object may have varying shapes and sizes, and the initial environment uses consistent room lighting to simplify detection. The first version will detect an object without a hand visible, followed by experiments involving an object held in a hand. The purpose is to understand fundamental computer vision concepts, including image acquisition, image segmentation, contour detection, coordinate estimation, and frame-by-frame object tracking.

## Project objectives

## Technical scope
|Item	          |Final decision                                   |
|-----------------|-------------------------------------------------|
|Camera	          |Logitech C270                                    |
|Computer         |	Intel NUC                                       |
|Language         |	Python                                          |
|Library          |	OpenCV                                          |
|Target           |	One predominantly black object                  |
|Background       |	Plain white wall                                |
|Lighting         |	Consistent room lighting                        |
|Object shape     |	Variable                                        |
|Object size      |	Variable, within camera's field of view         |
|Initial detection|	Object without hand visible                     |
|Later test       |	Object held in hand                             |
|Output           |	Bounding rectangle and center coordinates (X, Y)|

## Planned functionality
Detection, bounding box, coordinates, and tracking.

## Development status
<span style="background-color: #fff8c5; color: #9a6700; padding: 2px 8px; border-radius: 2em; font-size: 85%; font-weight: 600;">in-progress</span>