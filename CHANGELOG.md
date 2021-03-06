## Contributors

**[@mstraube](https://github.com/mstraube)**


## General

- Config file now has a `.conf` suffix.
- Neofetch now assumes target directories (config file and ASCII directory) at install time, this fixes problems with systems such as NixOS.


## Operating System

- Added support for Amazon Linux AMI.
- Added support for Sabotage Linux.
- Added support for Parsix GNU/Linux. **[@mstraube](https://github.com/mstraube)**
- Fixed Raspbian being detected as ChromeOS.


## Info

**CPU**

- [Linux] Fixed inaccurate output on ARM SoC devices.
- [Linux] Fixed CPU speed not appearing on PowerPC systems.
- [NetBSD] Added support for CPU temperature. (NOTE: This only supports newer Intel processors)
- Fixed inaccurate speed output in systems with CPU speed less than 1 GHz.
- Deprecated `cpu_shorthand` in favor of `cpu_brand`.

**Uptime**

- [AIX/IRIX] Fixed Neofetch crashing when calculating uptime.

**Terminal**

- [SSH] Fixed infinite loop if neofetch is run on non-interactive shells.

**Terminal Font**

- Added support for LXTerminal. **[@mstraube](https://github.com/mstraube)**
- Fixed Xfce4-terminal font output when system-wide font is used. **[@mstraube](https://github.com/mstraube)**

**Theme**

- [Qt/KDE] Fixed inaccurate theme naming. **[@mstraube](https://github.com/mstraube)**

**Window Manager**

- Fix incorrect output when using WindowMaker. **[@mstraube](https://github.com/mstraube)**

**Song**

- Added support for Pogo. **[@mstraube](https://github.com/mstraube)**

## Images

- Fixed division by 0 error in XTerm.
