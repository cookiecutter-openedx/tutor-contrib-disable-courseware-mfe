disable_courseware_mfe plugin for `Tutor <https://docs.tutor.overhang.io>`__
===================================================================================

Disables courseware micro front-end application functionality. Reverts the courseware UI to the legacy Django templating system 
that was used until the Maple release.

See: https://discuss.openedx.org/t/disabling-the-learning-mfe-in-maple-slightly-misleading-documentation/6320


Installation
------------

::

    pip install git+https://github.com/myusername/tutor-contrib-disable-courseware-mfe

Usage
-----

::

    tutor plugins enable disable_courseware_mfe


License
-------

This software is licensed under the terms of the AGPLv3.