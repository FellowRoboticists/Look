# -*- ruby -*-
# Look Arduino library
#
# Copyright 2013 Dave Sieh
# See LICENSE.txt for details.

LIB_DIR = 'lib'
BASE_DIR = '..'

LIBS = %w{ IrSensors PingSensor SoftServo }

LIBS.each do | lib |
  directory File.join(LIB_DIR, lib) do
    cp_r File.join(BASE_DIR, lib, LIB_DIR, lib), LIB_DIR
  end

  task :default => File.join(LIB_DIR, lib)
end
