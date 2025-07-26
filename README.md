# RASPBERRY PI OVERCLOCK

## **WARNING :** Use this only if you know what your doing **at your own risk**, We are not Responsible if something happens to your device.

### ❄️Highly Recomended to use Cooling❄️

# Raspberry Pi 3B

Tested on Raspberry Pi 3B (1GB RAM) with Bullseye 64-bit

- 1.375 Ghz (Stable)

# Raspberry Pi 4B

Tested on Raspberry Pi 4B (8GB RAM) with Bookworm 64-bit

- 2.147 Ghz (Stable)

- 2.200 Ghz (Not Fully Stable)

- 2.300 Ghz (Not Fully Stable)

- 2.400 Ghz (Unstable)

- 2.45 Ghz (Unstable)

`over_voltage` is not needed for latest versions, use only for older versions.
 
Change the `/boot/config.txt` or `/boot/firmware/config.txt` based on your OS version.


# Repo Structure
```bash
│   README.md
├───RaspberryPi 3B
│   └───1.375Ghz
│           overclock.txt
└───RaspberryPi 4B
    ├───Default
    │       config.txt
    └───OverClock
        ├───2.147Ghz
        │       config.txt
        ├───2.2Ghz
        │       config.txt
        ├───2.3Ghz
        │       config.txt
        ├───2.4Ghz
        │       config.txt
        └───2.45Ghz
               config.txt
```
