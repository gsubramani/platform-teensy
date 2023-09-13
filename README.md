# Teensy: development platform for [PlatformIO](http://platformio.org)

[![Build Status](https://github.com/tsandmann/platform-teensy/workflows/Examples/badge.svg)](https://github.com/tsandmann/platform-teensy/actions)

Teensy is a complete USB-based microcontroller development system, in a very small footprint, capable of implementing many types of projects. All programming is done via the USB port. No special programmer is needed, only a standard USB cable and a PC or Macintosh with a USB port.

* [Home](http://platformio.org/platforms/teensy) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/teensy.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

```ini
[env:teensy41]
platform = https://github.com/tsandmann/platform-teensy.git
board = ...
...
```

# Configuration

Please navigate to [documentation](http://docs.platformio.org/page/platforms/teensy.html).


# Working configuration: 
Platform teensy-ts @ 4.13.1+sha.f997c3b (required: git+git@github.com:gsubramani/platform-teensy.git)
├── framework-arduinoteensy @ 1.156.1+sha.6e3e4f7 (required: git+https://github.com/tsandmann/teensy-cores.git)
├── tool-teensy @ 1.155.0 (required: platformio/tool-teensy @ <2)
└── toolchain-arm-cortexm-linux @ 11.2.0-1+sha.8230779 (required: git+https://github.com/tsandmann/arm-cortexm-toolchain-linux.git)

Libraries
├── FNET @ 0.1.3+sha.be3a67e (required: git+https://github.com/vjmuzik/FNET.git)
├── FlexCAN_T4 @ 0.0.0+20230713184402.sha.d01d175 (required: git+https://github.com/gsubramani/FlexCAN_T4.git)
├── NativeEthernet @ 0.0.0+sha.cdf6b3a (required: git+https://github.com/vjmuzik/NativeEthernet.git)
├── freertos-teensy @ 10.4.5-2+sha.b8420ec (required: git+https://github.com/gsubramani/freertos-teensy.git)
├── help-protobuf @ 0.0.0+20230713184407.sha.ab9daa3 (required: git+git@github.com:gsubramani/help-protobuf.git)
├── help-protobuf @ 0.0.0+20220905191325 (required: file://../)
├── helpcore @ 0.0.0+20211024230012.sha.1e4b3ed (required: git+git@github.com:gsubramani/helpcore.git#ros_integration)
└── micro_ros_platformio @ 0.0.1+sha.35db5a9 (required: git+https://github.com/micro-ROS/micro_ros_platformio.git)
