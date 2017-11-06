.. include:: substitutions.txt

Installation
==================================

This document describes the installation and quick start of |m4| software.

==============================
Prerequisites
==============================

* 1GB of free hard disk storage
* 500MB of free RAM. For typical operating system use, we advise 2GB of system
  RAM for GNU/Linux and 4GB of system RAM for |win|.
* 2Ghz, dual core processor

Dependencies:
* The latest Windows Visual C++ 2008 Redistributable package, x86 version (independently on your OS being 64 or 32 bits): `vcredist`_.
* You will need `Xvid`_ MPEG4 video compression filter in order to export compressed videos of recorded frames.

.. _vcredist: https://www.microsoft.com/en-us/download/details.aspx?id=29
.. _Xvid: https://www.xvid.com/download/

=======
|win|
=======
|m4| for |win| 7 / 8 /10 can be obtained as a compressed zip file,
containing executable files, libraries and data.

Precompiled executables should be obtained by contacting directly TA Instruments support.



1. Extract all contents of the zip file to ``C:\misura``.
	.. tip:: Experienced users can choose their preferred location. 
	Please consider that placing the application on external hard-drives or slow storage devices can significantly affect startup time.
2. Browse to ``C:\misura``. You will find many files: locate the 3 main executable files, ``browser.exe``, ``acquisition.exe``, ``graphics.exe``.
3. For each executable file, right click on it and select "Create link". A new file will be created each time (E.g.: ``C:\misura\browser.exe - link``).
4. Copy or move the newly created link files to your Desktop, in order to find them more easily.

.. hint:: You should extract all contents of the zip file. Moving or copying the executables somewhere else 
	from the relative position they have in the extracted folder will cause severe errors. 
	Create shortcuts if you want to easily reach executables from your preferred positions.
	



----------
Upgrading
----------
Upgrading involves making a backup copy of the old application folder and installing the upgraded version over the old location.

	1. Rename ``C:\misura`` to ``C:\misura_backup``.
	2. Create an empty ``C:\misura`` folder and repeat installation steps from previous section.

========
|u|
========
|m4| for |ults| GNU/Linux operative system should be installed along with the full development environment.

Follow instructions contained in the `README`_.

.. _README: https://github.com/tainstr/misura.client
.. _public repository: https://github.com/tainstr/misura.client/releases
