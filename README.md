# Easy Grid View

> Angepasste Version von [Tasmota](https://github.com/arendst/Tasmota)

<hr></hr>

**In light of current events we like to support the people behind _PlatformIO Project_, especially Ivan Kravets, and wish them the strength to help stop the war. See [platformio-is-ukrainian-project-please-help-us-stop-the-war](https://community.platformio.org/t/platformio-is-ukrainian-project-please-help-us-stop-the-war/26330) for what you can do.**

<hr></hr>

## Änderungen zum Original Tasmota

## Installation

## Important User Compilation Information
If you want to compile Tasmota yourself keep in mind the following:

- For ESP8285 based devices only Flash Mode **DOUT** is supported. Do not use Flash Mode DIO / QIO / QOUT as it might seem to brick your device.
- For ESP8285 based devices Tasmota uses a 1M linker script WITHOUT spiffs **1M (no SPIFFS)** for optimal code space.
- To make compile time changes to Tasmota use the `user_config_override.h` file. It assures keeping your custom settings when you download and compile a new version. You have to make a copy from the provided `user_config_override_sample.h` file and add your setting overrides.

## Configuration Information

Please refer to the installation and configuration articles in the official [Tasmota documentation](https://tasmota.github.io/docs).

## Disclaimer

:warning: **DANGER OF ELECTROCUTION** :warning:

If your device connects to mains electricity (AC power) there is danger of electrocution if not installed properly. If you don't know how to install it, please call an electrician (***Beware:*** certain countries prohibit installation without a licensed electrician present). Remember: _**SAFETY FIRST**_. It is not worth the risk to yourself, your family and your home if you don't know exactly what you are doing. Never tinker or try to flash a device using the serial programming interface while it is connected to MAINS ELECTRICITY (AC power).

We don't take any responsibility nor liability for using this software nor for the installation or any tips, advice, videos, etc. given by any member of this site or any related site.

## Support Information

For a database of supported devices see [Tasmota Device Templates Repository](https://templates.blakadder.com)

### Official Tasmota Documentation

* [Documentation Site](https://tasmota.github.io/docs): For information on how to flash Tasmota, configure, use and expand it
* [FAQ and Troubleshooting](https://tasmota.github.io/docs/FAQ/): For information on common problems and solutions.
* [Commands Information](https://tasmota.github.io/docs/Commands): For information on all the commands supported by Tasmota.

## Credits

This fork is based on the excellent work of the [Tasmota project](https://github.com/arendst/Tasmota) and its many contributors.

## License

This program is licensed under GPL-3.0-only
