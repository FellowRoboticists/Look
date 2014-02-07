# -*- ruby -*-
# Look Arduino library
#
# Copyright 2013 Dave Sieh
# See LICENSE.txt for details.
#
# Put the parent directory on the Ruby Load path
$: << File.dirname(File.dirname(__FILE__))

# Bring in the task support
require 'arduino-tasks/tasks'
include ArduinoTasks

BASE_DIR = '..'

env = ArduinoEnvironment.new BASE_DIR

LIBS = [
  library('IrSensors'),
  library('PingSensor'),
  library('SoftServo')
]

create_all_library_tasks env, LIBS, :default
