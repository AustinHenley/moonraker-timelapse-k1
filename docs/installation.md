# Installation

This document provides a guide on how to install Moonraker-timelapse component.
As this is a plugin to Moonraker, Moonraker and klipper needs to be installed
before hand.

## Installing the component

To install the Component you need to connect to your Creality K1/Max via ssh and
execute following commands:

```
cd ~/
git clone https://github.com/AustinHenley/moonraker-timelapse-k1.git
cd ~/moonraker-timelapse-k1
mv component/timelapse.py /usr/data/moonraker/moonraker/moonraker/components/
mv klipper_macro/timelapse.cfg /usr/data/printer_data/config/
```

This will clone the repository and move the necessary files.

# Configuration

Please see [configuration.md](configuration.md) for details on how to
configure the timelapse component.
