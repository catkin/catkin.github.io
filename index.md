---
layout: default
title: catkin
---

catkin is a [CMake](cmake.org) based build system which emphasizes building many projects together simultaneously, which may be developed in a distributed manner.
catkin was developed to support the [ROS](http://ros.org) ecosystem, which has a federated approach to software development.
As a result, building ROS requires that you build many (potentially hundreds) of CMake based projects together.
One of the goals of catkin was to remain as close to standard CMake as possible.
As a result catkin is implemented as a few CMake macros on top of the normal CMake interface and some tools to automate the normal CMake workflow which helps it scale to many federated projects.

There are many catkin resources available for users interested in getting involved on the ROS wiki at wiki.ros.org:

[http://wiki.ros.org/catkin](http://wiki.ros.org/catkin)
