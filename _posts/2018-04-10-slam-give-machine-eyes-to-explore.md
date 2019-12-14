---
title: "SLAM: Give Machine Eyes to Explore"
excerpt: "Who do robot and vehcile see the world?"
header:
  overlay_image: /assets/images/monocular-slam.jpg
  overlay_filter: 0.5
categories:
  - Augmented Reality
  - Computer Vision
tags:
  - computer vision
---

What is SLAM? It may be hard to understand if you are not familiar with Computer Vision or three-dimensional mapping. But it is not hard to know its importance: robots without SLAM – Simultaneous Localization and Mapping – are just as useless as smartphone without WIFI or mobile network. Therefore, in order to improve the applications and user experience of Augmented Reality(AR)/Virtual Reality (VR), robots, drones or driverless cars, SLAM is the essential technical core that needs heavy investment.

# What Does SLAM Solve

SLAM utilises various sensors, such as a camera or a laser radar, to locate the robot or subject itself in three-dimensional space and construct a map of its surrounding environment. Both these functions need to be carried out simultaneously because, if we imagine for a moment, a Roomba that starts cleaning only after scanning the entire room, or a driverless car that can only construct a map of surrounding obstacles after running into a tree… Today, in many hot high-tech discussions, SLAM is the unsung hero that has been applied to many projects in these fields:

* In the field of VR/AR, a device can better render an overlying artificial object when given a constructed map and the current visual angle. A well-performing SLAM will make VR/AR look more realistic and convincing.
* In the field of unmanned aerial vehicle, SLAM will help drones construct local maps, facilitating their ability to plan routes and bypass obstacles.
* In the field of automotive, driverless cars can determine its position and orientation by analysing the associated camera images with SLAM. Such techniques can also be integrated with other localization techniques to provide better accuracy.
* In the field of robotic localization and navigation, SLAM can be used to generate a map. Based on the map, robots can plan routes, explore and navigate independently.

# What SLAM Methods Do We Have?

SLAM has many categories based on different sensors we use. I will explain each of them one by one.

* 2D/3D SLAM based on laser radar
* RGBD SLAM based on cameras with depth sensors
* visual SLAM (vSLAM) that is based on camera, and
* visual inertial odometry (VIO) that based on camera and inertia measurement unit

The development 2D/3D SLAM that based on laser radar has been mature and applied to numerous products in our daily life. The theoretical framework of 2D/3D SLAM has been established by Sebastian Thrun in 2005. It has been over ten years since the invent of grid mapping, which has been commonly used in sweeping robots such as Roomba. In 2016, Google also has open-sourced the 2D/3D SLAM program cartographer, which can together make use of inertia measurement unit (IMU) to execute both 2D and 3D SLAM.

<figure>
	<a href="/assets/images/slam-map.png"><img src="/assets/images/slam-map.png"></a>
	<figcaption>SLAM Map Constructed by Roomba</figcaption>
</figure>

Of course, not all items can be equipped with laser radar. To carry out SLAM with miniaturised products, companies have ventured into alternatives such as RGBD SLAM. This type of SLAM works on the visual sensor that combined with the depth. For example, since Microsoft launched Kinect, researchers have developed algorithms, including KinectFusion and Kintinuous, that effectively process the visual and depth data to locate and construct 3D mapping. iPhone X uses a combination of infrared emitter and sensor (which it calls TrueDepth) to paint 30,000 points of infrared light on and around your face and also capture flat or 2D infrared snapshots. For the points, the reflection is measured, which allows it to calculate depth and angle from the camera for each dot and construct a depth map. (Sadly I do not have access to raw censor data to extend its functionality beyond FaceID unless I work for Apple, but it is understandable that Apple does so for security concerns)

The later two categories, vSLAM and VIO, have only just been developed and are still far from maturity. However, because visual sensors such as single-lens camera, double-lens camera and fisheye cameras, are cheap and applicable for both indoor and outdoor scenarios, vSLAM has become a hot topic of research. Nowadays, more methods of Computer Vision, specifically, structure-from-motion and bundle adjustment, have been applied to vSLAM. However, visual sensor cannot work in the environment without texture. Therefore, inertial measurement unit (IMU) is needed to conjecture the posture of camera. Yet, the applications of vSLAM and VIO are still limited: usually they need to work together with other sensors in a controlled environment.

The theory of vSLAM is clear: extract feature points in the associated images and apply geometry to give information of spatial distribution. But in reality, there is no algorithm that has both good performance and rapid processing speed to fulfill vSLAM. Algorithms such as SIFT, SURF, ORB or FAST, are either efficient or more accurate, but not both.

# The Future of SLAM

In the short term, we can expect some improvements in the theoretical framework in vSLAM, but in the long run, development of new types of sensor will ensure brighter future of SLAM. The more high-quality raw data, the less pressure the SLAM algorithms have.

Since machine learning and deep learning has become so popular in various fields, some researchers try to implement deep learning in SLAM. Yet these trials have not demonstrated the overwhelming advantage over traditional geometry. Maybe specific process can be replaced by deep learning, but there is no promise that it will take over the whole SLAM current framework.

In the future, integration between SLAM and other fields including speech recognition may improve SLAM in terms of speed and performance. As you can see, we still have a long way to go to give machines eyes to explore by themselves.