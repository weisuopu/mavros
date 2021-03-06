^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package libmavconn
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.4 (2015-01-06)
------------------

0.9.3 (2014-12-30)
------------------
* mavconn: Add ASLUAV dialect selection.
* Contributors: Vladimir Ermakov

0.9.2 (2014-11-04)
------------------
* Fix libmavconn include destination.
  Before that change headers installed in include/libmavconn (package name)
  and it broke release builds for 0.9.1 and 0.8.4.
  Strange that prerelease build runs without errors.
  Issue `#162 <https://github.com/vooon/mavros/issues/162>`_.
* Contributors: Vladimir Ermakov

0.9.1 (2014-11-03)
------------------
* Fix libmavconn deps.
  Releases 0.9 and 0.8.3 ar broken because i forgot to add mavlink dep.
* Contributors: Vladimir Ermakov

0.9.0 (2014-11-03)
------------------

0.8.2 (2014-11-03)
------------------
* REP140: update package.xml format.
  Hydro don't accept this format correctly,
  but after split i can update.
* Contributors: Vladimir Ermakov

0.8.1 (2014-11-02)
------------------
* mavconn `#161 <https://github.com/vooon/mavros/issues/161>`_: try to fix hydro build
* mavconn `#161 <https://github.com/vooon/mavros/issues/161>`_: Move mavconn tests.
* mavconn `#161 <https://github.com/vooon/mavros/issues/161>`_: Fix headers used in mavros. Add readme.
* mavconn `#161 <https://github.com/vooon/mavros/issues/161>`_: Fix mavros build.
* mavconn `#161 <https://github.com/vooon/mavros/issues/161>`_: Move library to its own package
  Also rosconsole replaced by console_bridge, so now library can be used
  without ros infrastructure.
* Contributors: Vladimir Ermakov
