OSRFramework
============

OSRFramework: Open Sources Research Framework

Copyright (C) 2016  F. Brezo and Y. Rubio, i3visio

[![Version in PyPI](https://img.shields.io/pypi/v/osrframework.svg)]()
[![Downloads/Month in PyPI](https://img.shields.io/pypi/dm/osrframework.svg)]()
[![License](https://img.shields.io/badge/license-GNU%20General%20Public%20License%20Version%203%20or%20Later-blue.svg)]()

1 - Description
---------------

OSRFramework is a GPLv3+ set of libraries developed by i3visio to perform Open Source Intelligence tasks. They include references to a bunch of different applications related to username checking, information leaks research, deep web search, regular expressions extraction and many others. At the same time, by means of ad-hoc Maltego transforms, OSRFramework provides a way of making these queries graphically.


2 - License: GPLv3+
-------------------

This is free software, and you are welcome to redistribute it under certain conditions.

	This program is free software: you can redistribute it and/or modify
	it under the terms of the GNU General Public License as published by
	the Free Software Foundation, either version 3 of the License, or
	(at your option) any later version.

	This program is distributed in the hope that it will be useful,
	but WITHOUT ANY WARRANTY; without even the implied warranty of
	MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
	GNU General Public License for more details.

	You should have received a copy of the GNU General Public License
	along with this program.  If not, see <http://www.gnu.org/licenses/>.


For more details on this issue, check the [COPYING](COPYING) file.

3 - Installation
----------------

Fast way to do it on any system:
```
pip install osrframework
```
Under MacOS or Linux systems, you may need to do this as superuser:
```
sudo pip install osrframework
```
This will manage all the dependencies for you.

If you needed further information, check the [INSTALL.md](INSTALL.md) file.

4 - Basic usage
---------------

If everything went correctly (we hope so!), it's time for trying usufy.py, mailfy.py and so on. But we are they? They are installed in your path meaning that you can open a terminal anywhere and typing the name of the program (seems to be an improvement from previous installations...). Examples:
```
usufy.py -n i3visio febrezo yrubiosec -p twitter facebook
searchfy.py -q "i3visio"
mailfy.py -n i3visio
```

Type -h or --help to get more information about which are the parameters of each application.

You can find the configuration files in a folder created in your user home:
```
# Configuration files for Linux and MacOS
~/.config/OSRFramework/
# Configuration files for Windows
%APP_DATA%/OSRFramework/
```

OSRFramework will look for the configuration settings stored there. You can add new credentials there and if something goes wrong, you can always restore the files stored in the `defaults` subfolder.

5 - HACKING
-----------

If you want to extend the functionalities of OSRFramework and you do not know where to start from, check the [HACKING.md](HACKING.md) file.

6 - AUTHORS
-----------

More details about the authors in the [AUTHORS.md](AUTHORS.md) file.
