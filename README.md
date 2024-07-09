# Espressif 32: development platform for [PlatformIO](https://platformio.org)

> [!NOTE]  
> This repository brings platform-replacement URL that can be used to get newer Arduino for PlatformIO.
> My intention was to create one place for platform dependency for all ksIotFrameworkLib based projects.
>
> Some packages come from Tasmota, many thanks to [Jason2866](https://github.com/Jason2866) for sharing them.
> Original repository can be found here: [tasmota/platform-espressif32](https://github.com/tasmota/platform-espressif32).

[![Build Status](https://github.com/platformio/platform-espressif32/workflows/Examples/badge.svg)](https://github.com/platformio/platform-espressif32/actions)

ESP32 is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and Bluetooth. ESP32 integrates an antenna switch, RF balun, power amplifier, low-noise receive amplifier, filters, and power management modules.

* [Home](https://registry.platformio.org/platforms/platformio/espressif32) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/espressif32.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version

See `platform` [documentation](https://docs.platformio.org/en/latest/projectconf/sections/env/options/platform/platform.html#projectconf-env-platform) for details.

```ini
[env:stable]
; recommended to pin to a version, see https://github.com/platformio/platform-espressif32/releases
; platform = espressif32 @ ^6.0.1
platform = espressif32
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-espressif32.git
board = ...
...
```

# Configuration
Please navigate to [documentation](https://docs.platformio.org/page/platforms/espressif32.html).
