#!/usr/bin/env python

import sys
import Image
import select
import v4l2
import fcntl

vd = open('/dev/video1', 'rw')
cp = v4l2.v4l2_streamparm()
fcntl.ioctl(vd, v4l2.v4l2_streamparm, cp)
