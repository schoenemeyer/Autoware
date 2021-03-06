^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package autoware_camera_lidar_calibrator
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.9.0 (2018-10-31)
------------------
* [fix] Added option to publish to specific camera frame on camera publisher (`#1565 <https://github.com/kfunaoka/Autoware/issues/1565>`_)
  * * Added option to publish to specific camera frame on camera publisher
  * fixes to the node
  * Added New line to UI on each param.
  * * Updates to launch files using calibration publisher
  * Updated naming after develop merge
  * Updated suscription type to topic for calibration publisher
* [fix]Removed python yaml dependency that was causing issues. Tested on kinetic/opencv3.3 (`#1622 <https://github.com/kfunaoka/Autoware/issues/1622>`_)
* Fix/intrinsic calibration gui aa (`#1581 <https://github.com/kfunaoka/Autoware/issues/1581>`_)
  * Fixed calibration UI text anti-aliasing in CV3
  * tested on cv2 and cv3 (indigo and kinetic)
* Contributors: Abraham Monrroy Cano, Jacob Lambert

1.8.0 (2018-08-31)
------------------
* [Fix] Moved C++11 flag to autoware_build_flags (`#1395 <https://github.com/CPFL/Autoware/pull/1395>`_)
* [Feature] Makes sure that all binaries have their dependencies linked (`#1385 <https://github.com/CPFL/Autoware/pull/1385>`_)
* [Fix] Extend and Update interface.yaml (`#1291 <https://github.com/CPFL/Autoware/pull/1291>`_)
* Contributors: Esteve Fernandez, Kenji Funaoka

1.7.0 (2018-05-16)
------------------
* update Version from 1.6.3 to 1.7.0 in package.xml and CHANGELOG.rst
* Modify package xml version other than 1.6.3
* Remove history of sub-branches
* Add automatically-generated CHANGELOG.rst
* Fix/cmake cleanup (`#1156 <https://github.com/CPFL/Autoware/pull/1156>`_)
  * Initial Cleanup
  * fixed also for indigo
  * kf cjeck
  * Fix road wizard
  * Added travis ci
  * Trigger CI
  * Fixes to cv_tracker and lidar_tracker cmake
  * Fix kitti player dependencies
  * Removed unnecessary dependencies
  * messages fixing for can
  * Update build script travis
  * Travis Path
  * Travis Paths fix
  * Travis test
  * Eigen checks
  * removed unnecessary dependencies
  * Eigen Detection
  * Job number reduced
  * Eigen3 more fixes
  * More Eigen3
  * Even more Eigen
  * find package cmake modules included
  * More fixes to cmake modules
  * Removed non ros dependency
  * Enable industrial_ci for indidog and kinetic
  * Wrong install command
  * fix rviz_plugin install
  * FastVirtualScan fix
  * Fix Qt5 Fastvirtualscan
  * Fixed qt5 system dependencies for rosdep
  * NDT TKU Fix catkin not pacakged
  * Fixes from industrial_ci
* [fix] Added missing Qt5Core dependency for PCL in autoware_calibration package (`#1149 <https://github.com/CPFL/Autoware/pull/1149>`_)
  * Added missing Qt5Core dependency for PCL
  * Removed unnecessary library linking
* Output file updated
* fixed matlab chessboard detection
* Initial Release Autoware Camera-LiDAR calibration tool (`#1131 <https://github.com/CPFL/Autoware/pull/1131>`_)
  * Initial Release Autoware Camera-LiDAR calibration tool
  * Update README
  File is saved now
  * Editorial changes to readme file.
* Contributors: AMC, Abraham Monrroy, Jacob Lambert, Kenji Funaoka, Kosuke Murakami

1.6.3 (2018-03-06)
------------------

1.6.2 (2018-02-27)
------------------

1.6.1 (2018-01-20)
------------------

1.6.0 (2017-12-11)
------------------

1.5.1 (2017-09-25)
------------------

1.5.0 (2017-09-21)
------------------

1.4.0 (2017-08-04)
------------------

1.3.1 (2017-07-16)
------------------

1.3.0 (2017-07-14)
------------------

1.2.0 (2017-06-07)
------------------

1.1.2 (2017-02-27 23:10)
------------------------

1.1.1 (2017-02-27 22:25)
------------------------

1.1.0 (2017-02-24)
------------------

1.0.1 (2017-01-14)
------------------

1.0.0 (2016-12-22)
------------------
