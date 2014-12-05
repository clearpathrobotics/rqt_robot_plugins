^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rqt_rviz
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.3.6 (2014-07-11)
------------------

0.3.5 (2014-06-02)
------------------
* fix compilation on OS X (`#64 <https://github.com/ros-visualization/rqt_robot_plugins/issues/64>`_)

0.3.4 (2014-05-07)
------------------
* add menu hiding and config as command-line args (`#62 <https://github.com/ros-visualization/rqt_robot_plugins/pull/62>`_)

0.3.3 (2014-01-28)
------------------

0.3.2 (2014-01-08)
------------------
* add groups for rqt plugins (`ros-visualization/rqt_common_plugins#167 <https://github.com/ros-visualization/rqt_common_plugins/issues/167>`_)

0.4.0 (2014-12-05)
------------------
* Temporarily store QByteArrays when parsing args
  Parameters vanish if there is no temporary storage for args obtained
  from qargv.
* 0.3.6
* update changelogs
* 0.3.5
* update changelogs
* Update rviz.cpp
  Fix compilation on OS X. See `#64 <https://github.com/clearpathrobotics/rqt_robot_plugins/issues/64>`_.
* Fix rqt_rviz CMakeLists.txt
  We need to link in Boost.ProgramOptions, otherwise linking fails on OS X.
* 0.3.4
* update changelogs
* Added menu hiding and config as command-line args.
  A bit messy because the toplevel script needs to tell RQT about which
  arguments belong to the plugins - so the arguments are specified twice,
  once in the script and once in the CPP code where they are actually
  used.
* 0.3.3
* update changelogs
* "0.3.2"
* update changelogs
* add groups for rqt plugins (`ros-visualization/rqt_common_plugins#167 <https://github.com/ros-visualization/rqt_common_plugins/issues/167>`_)
* Contributors: Alex Bencz, Dirk Thomas, Nikolaus Demmel

0.3.1 (2013-10-09)
------------------

0.3.0 (2013-08-28)
------------------

0.2.16 (2013-07-09)
-------------------
* First public release into Hydro

0.2.15 (2013-04-25)
-------------------

0.2.14 (2013-04-12)
-------------------

0.2.13 (2013-04-09)
-------------------

0.2.12 (2013-04-06 18:22)
-------------------------

0.2.11 (2013-04-06 18:00)
-------------------------

0.2.10 (2013-04-04)
-------------------

0.2.9 (2013-03-07)
------------------

0.2.8 (2013-01-11)
------------------

0.2.7 (2012-12-23 15:58)
------------------------
* restore rviz plugin and add it to metapackage (that was done in 0.2.6)
* first public release for Groovy
