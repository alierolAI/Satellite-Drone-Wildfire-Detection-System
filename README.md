# Satellite-Drone-Wildfire-Detection-System

## AI-Powered Layered Wildfire Detection and Verification Architecture Using Satellite and UAV Imagery

This graduation project proposes a layered autonomous wildfire detection system that combines multispectral Sentinel-2 satellite imagery, UAV-based verification mechanisms, and YOLO-based deep learning object detection architectures.

Unlike traditional wildfire monitoring approaches that rely on a single sensing platform, the proposed architecture integrates satellite-based large-area monitoring with UAV-based high-resolution verification in order to improve early wildfire detection reliability while minimizing operational cost and false positive alarms.

Instead of focusing on physical hardware simulation, this work concentrates on designing and experimentally validating the computer vision decision mechanisms required for an autonomous wildfire monitoring pipeline.

The proposed architecture consists of four autonomous layers:

* NASA FIRMS / VIIRS hotspot triggering
* Sentinel-2 multispectral wildfire analysis
* UAV-based fallback verification
* Alarm and notification system

Within the scope of this study:

* ~19,000 multispectral Sentinel-2 images
* ~27,000 UAV wildfire images

were comparatively analyzed using:

* YOLOv8
* YOLOv10
* YOLOv12

architectures.

Additionally, multiple spectral compositions including:

* SWIR
* Urban False Color
* False Color
* True Color

were evaluated in order to identify the most effective spectral representation for wildfire detection under smoke-heavy real-world conditions.

## internal test prediction
### YoloV12s 
<img width="1200" height="860" alt="cl6azgmfw0004f0557iqa1usw_6_SWIR_jpg rf e7a3f58bf1c1ce6eafb874f16f7b342d" src="https://github.com/user-attachments/assets/057fa224-0eab-480b-a84e-de5eb9a1d6f5" />
### yoloV10s 
<img width="1200" height="860" alt="cl6azgmfw0004f0557iqa1usw_6_SWIR_jpg rf e7a3f58bf1c1ce6eafb874f16f7b342d" src="https://github.com/user-attachments/assets/86968323-0a17-4e6f-927c-7aee59e2b82c" />
### yoloV8s
<img width="1200" height="860" alt="cl6azgmfw0004f0557iqa1usw_6_SWIR_jpg rf e7a3f58bf1c1ce6eafb874f16f7b342d" src="https://github.com/user-attachments/assets/53c1ccb2-0f0e-49d3-a909-1fa45b13991d" />







