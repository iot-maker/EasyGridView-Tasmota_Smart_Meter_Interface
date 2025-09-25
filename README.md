# Easy Grid View

> Angepasste Version von [Tasmota](https://github.com/arendst/Tasmota)

<hr></hr>

**In light of current events we like to support the people behind _PlatformIO Project_, especially Ivan Kravets, and wish them the strength to help stop the war. See [platformio-is-ukrainian-project-please-help-us-stop-the-war](https://community.platformio.org/t/platformio-is-ukrainian-project-please-help-us-stop-the-war/26330) for what you can do.**

<hr></hr>

## Änderungen zum Original Tasmota

Diese Firmware ist spezifisch auf IR Leseköpfe für Stromzähler ausgelegt. Die 'Edit Script'-Konsole wurde erweitert und verfügt über eine Suchfunktion für Stromzählerskripte.

<details>
<summary>Schritt 1: Konsole öffnen</summary>

Drücken sie den grünen 'Edit Script'-Button, um die Konsole zu öffnen.

<img width="364" height="471" alt="MainMenu" src="https://github.com/user-attachments/assets/c1f7cc1b-f18d-44ec-a55e-067ef02d2c4b" />

</details>

<details>
<summary>Schritt 2: Stromzählerskript suchen</summary>

Geben sie in dem Feld 'Search meter model' den Namen ihres Stromzählers ein und drücken sie auf 'Load Script'.

<img width="600" height="620" alt="ScriptingConsole_Search" src="https://github.com/user-attachments/assets/7d8ceb85-4973-4073-b48e-539108c1d79d" />

</details>

<details>
<summary>Schritt 3: Skript aktivieren und speichern</summary>

Setzen sie den Haken bei 'Script enable' und drücken sie auf 'Save'. Wenn sie nun zum Main Menu zurückkehren, dürften ihnen die ausgelesenen Werte angezeigt werden.

<img width="600" height="620" alt="ScriptingConsole_Enabled" src="https://github.com/user-attachments/assets/db0667a2-3182-47aa-92ca-bb9f1df764e9" />

</details>

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
