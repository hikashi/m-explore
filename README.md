# m-explore

Update / Difference from the main file 
----------
- added custom name support from different robot namespace.
- work with Ubuntu 18.04 and ROS Melodic



[![Build Status](http://build.ros.org/job/Kdev__m_explore__ubuntu_xenial_amd64/badge/icon)](http://build.ros.org/job/Kdev__m_explore__ubuntu_xenial_amd64)

ROS packages for multi robot exploration.

Installing
----------

Packages are released for ROS Kinetic and ROS Lunar.

```
	sudo apt install ros-${ROS_DISTRO}-multirobot-map-merge ros-${ROS_DISTRO}-explore-lite
```

Building
--------

Build as standard catkin packages. There are no special dependencies needed
(use rosdep to resolve dependencies in ROS). You should use brach specific for
your release i.e. `kinetic-devel` for kinetic. Master branch is for latest ROS.

WIKI
----

Packages are documented at ROS wiki.
* [explore_lite](http://wiki.ros.org/explore_lite)
* [multirobot_map_merge](http://wiki.ros.org/multirobot_map_merge)

COPYRIGHT
---------

Packages are licensed under BSD license. See respective files for details.
