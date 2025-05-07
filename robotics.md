---
title: Prasanth Ananth
description: Robotics
layout: default
---

# Warehouse inventory management 

<img src="/images/aims-overview.png" alt="System overview" width="750">

This is work I directed at [Sientis](https://www.sientis.ai/) (a Nokia venture). Warehouses perform inventory cycle counting manually
which is slow and costly. We developed indoor drones which fly autonomously and capture images of inventory 
locations performing inventory counting 30x faster. The drones use in-house computer vision localization 
without requiring any additional infrastructure (such as beacons or tags). 

<img src="/images/sientis-drone.webp" alt="Drone" width="350">

We built an industry-leading compact and quiet drone that can navigate narrow aisles and captures 4K images.
The images are uploaded to the on-premise edge server and public cloud where the images are processed and
the inventory results are presented to the warehouse user.

**Technologies**: ROS, PX4, VIO, VPS, Sensor fusion, Path planning, Trajectory control, Imaging, Gazebo, Isaac Sim

# Plant monitoring in vertical farms

This is work I directed at [Nokia Bell Labs](https://www.nokia.com/bell-labs/), where we collaborated with [AeroFarms](https://www.aerofarms.com/). In indoor vertical farms, 
the plants go through a growth cycle of few weeks during which they need to be inspected every day by
plant scientists, which is time-consuming and thus costly. We developed indoor drones which fly autonomously
and capture high-resolution images of every plant tray. The drones use computer vision localization with 
Visual Inertial Odometry (VIO) and drift correction using fiducials. The images are uploaded to the
on-premise edge server where the images are processed and the plant analytics results are presented 
to the plant scientists.

**Technologies**: ROS, PX4, VIO, AprilTags, Sensor fusion, Path planning, Imaging, Gazebo, AirSim

Featured in [**IEEE Spectrum**](https://spectrum.ieee.org/industrial-automation-monitor-vertical-farms)

# Object tracking and following

<img src="/images/track-and-follow.png" alt="Drone" width="350">

This is work I directed at [Nokia Bell Labs](https://www.nokia.com/bell-labs/). The Nokia drones business required the tracking of objects and
following the object's movement using the gimbal of an outdoor surveillance drone. We developed a solution
with object tracking and a PID-based controller to control the pan-tilt-zoom of the gimbal. 
We then extended this work to estimate the position of the object and have the drone follow it 
from a specified distance.

**Technologies**: ROS, PX4, GPS, Path planning, Video streaming, Gazebo, AirSim

# Precision landing 

<img src="/images/prec-land.png" alt="Drone" width="300">

This is work I directed at [Nokia Bell Labs](https://www.nokia.com/bell-labs/). The Nokia drones business had a requirement to precisely land 
(cm-level accuracy) an outdoor drone on a docking station for charging. We developed two solutions: one
using AprilTags and computer vision, and another using an IR beacon, each with its own pros and cons.
We then extended this work to add safety mechanisms for when the drone loses sight of the tag or beacon.

**Technologies**: ROS, ArduPilot, PX4, GPS-RTK, AprilTags, Waypoint planning, Video streaming, Gazebo

# Gesture-controlled drones

<img src="/images/gesture-drone.png" alt="Drone" width="300">

This is work I directed at [Nokia Bell Labs](https://www.nokia.com/bell-labs/), which was in part a 
collaboration with artists-in-residence. We used a wearable sleeve with embedded sensors and software
to recognize gestures. We developed a system where the gesture commands from the sleeve are translated
into drone movements and a person could tele-operate the drone either indoor or outdoor. This demo
was adapted and integrated into a live dance performance by the artists.

**Technologies**: ROS, PX4, GPS, MoCap, Optical Flow

Featured in [**Wired**](https://www.wired.com/story/bell-labs-eat-only-human-mana-contemporary/)