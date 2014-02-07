Look Arduino Library
====================

The Look library allows the robot to sense its environent via a scanning
Ping))) sensor and some IR reflectance sensors.

Building/Testing
================

Preparation:

1. Determine the directory in which you will place the Look project
2. Clone the https://github.com/FellowRoboticists/arduino-tasks project. This provides the necessary ruby tasks use by the rake command.
3. Clone the https://github.com/FellowRoboticists/Look project.
4. In the Look project directory, invoke the 'rake' command. This will automatically pull all the dependency libraries from GitHub and prepare the ino project for building.

To build the example sketch:

```
ino build
```

To upload the example sketch:

```
ino upload
```

Copyright
=========
Copyright 2013,2014 Dave Sieh

See LICENSE.txt for details.
