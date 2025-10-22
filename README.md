# Easy Grid View

> Angepasste Version von [Tasmota](https://github.com/arendst/Tasmota)

## Änderungen zum Original Tasmota

Diese Firmware ist spezifisch auf IR Leseköpfe für Stromzähler ausgelegt. Die 'Edit Script'-Konsole wurde erweitert und verfügt über eine Suchfunktion für Stromzählerskripte.


### <summary>Schritt 1: Konsole öffnen</summary>

Drücken sie den grünen 'Edit Script'-Button, um die Konsole zu öffnen.

<img width="364" height="471" alt="MainMenu" src="https://github.com/user-attachments/assets/c1f7cc1b-f18d-44ec-a55e-067ef02d2c4b" />


### <summary>Schritt 2: Stromzählerskript suchen</summary>

Geben sie in dem Feld 'Search meter model' den Namen ihres Stromzählers ein und drücken sie auf 'Load Script'.

<img width="600" height="620" alt="ScriptingConsole_Search" src="https://github.com/user-attachments/assets/7d8ceb85-4973-4073-b48e-539108c1d79d" />


### <summary>Schritt 3: Skript aktivieren und speichern</summary>

Setzen sie den Haken bei 'Script enable' und drücken sie auf 'Save'. Wenn sie nun zum Main Menu zurückkehren, dürften ihnen die ausgelesenen Werte angezeigt werden.

<img width="600" height="620" alt="ScriptingConsole_Enabled" src="https://github.com/user-attachments/assets/db0667a2-3182-47aa-92ca-bb9f1df764e9" />


## Installation

### 1. Methode – Over-the-air (OTA)
  1. Die korrekte '.bin'-Datei [hier](https://github.com/iot-maker/EasyGridView-Tasmota_Smart_Meter_Interface/releases/tag/v15.0.1) je nach ESP Modell runterladen
  2. Im Tasmota Webinterface auf "Firmware Upgrade" navigieren
  3. '.bin'-Datei auswählen und auf "Start upgrade" klicken

### 2. Methode – Flashen
_**ACHTUNG: Beim Flashen werden alle Daten auf dem Gerät gelöscht!**_
  1. Nutzen sie diesen [Web Flasher](https://selbstbau-pv.de/pages/tasmota-web-flasher). Hier muss keine bestimmte Version ausgewählt werden. Abhängig von dem angeschlossenen Gerät wird automatisch die passende Version installiert.
  2. Falls das nicht klappen sollte, kann [hier](https://github.com/iot-maker/EasyGridView-Tasmota_Smart_Meter_Interface/releases/tag/v15.0.1) die factory.bin für das passende ESP Modell heruntergeladen und über den [Tasmota Web Flasher](https://tasmota.github.io/install/) auf das Gerät geflashed werden.


## Konfigurationsinformationen

Bitte lesen Sie die Artikel zur Installation und Konfiguration in der offiziellen [Tasmota-Dokumentation](https://tasmota.github.io/docs).

## Disclaimer

:warning: **STROMSCHLAGGEFAHR** :warning:

Wenn Ihr Gerät an das Stromnetz (Wechselstrom) angeschlossen wird, besteht bei unsachgemäßer Installation die Gefahr eines Stromschlags. Wenn Sie nicht wissen, wie es installiert wird, wenden Sie sich bitte an einen Elektriker (***Achtung:*** In einigen Ländern ist die Installation ohne einen zugelassenen Elektriker verboten). Denken Sie daran: _**SICHERHEIT GEHT VOR**_. Es lohnt sich nicht, ein Risiko für sich selbst, Ihre Familie und Ihr Zuhause einzugehen, wenn Sie nicht genau wissen, was Sie tun. Basteln Sie niemals an einem Gerät herum und versuchen Sie niemals, es über die serielle Programmierschnittstelle zu flashen, während es an das STROMNETZ (Wechselstrom) angeschlossen ist.

Wir übernehmen keine Verantwortung oder Haftung für die Verwendung dieser Software oder für die Installation oder Tipps, Ratschläge, Videos usw., die von Mitgliedern dieser Website oder einer verwandten Website gegeben werden.

### Offizielle Tasmota Dokumentation

* [Dokumentationsseite](https://tasmota.github.io/docs): Informationen zum Flashen, Konfigurieren, Verwenden und Erweitern von Tasmota
* [FAQ und Fehlerbehebung](https://tasmota.github.io/docs/FAQ/): Informationen zu häufigen Problemen und Lösungen.
* [Informationen zu Befehlen](https://tasmota.github.io/docs/Commands): Informationen zu allen von Tasmota unterstützten Befehlen.

<hr></hr>

**Angesichts der aktuellen Ereignisse möchten wir die Menschen hinter dem PlatformIO-Projekt, insbesondere Ivan Kravets, unterstützen und wünschen ihnen die Kraft, zur Beendigung des Krieges beizutragen. Unter [platformio-is-ukrainian-project-please-help-us-stop-the-war](https://community.platformio.org/t/platformio-is-ukrainian-project-please-help-us-stop-the-war/26330) erfahren Sie, was Sie tun können.**

<hr></hr>

## Credits

Diese Fork basiert auf der hervorragenden Arbeit des [Tasmota-Projekts](https://github.com/arendst/Tasmota) und seiner zahlreichen Mitwirkenden.

## License

This program is licensed under GPL-3.0-only
