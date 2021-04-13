# jetson-oled

A simple example driving the 0.96 inch OLED display over I2C on the NVIDIA Jetson nano.

It provides various bits of information about the host: the IPv4 address of the default host interface, "live" gateway and internet connectivity status, "live" UTC time, and "live" uptime, and load average.

Usage:

- install an I2C OLED display (wired to +3.3V, GND, SDA, and SCL)
- install docker and git
- git clone this repo, and cd into it
- run "make build"
- run "make run"

Based on the more comprehensive example in:
  [https://github.com/MegaMosquito/oled](https://github.com/MegaMosquito/oled)

Written by mosquito@darlingevil.com
