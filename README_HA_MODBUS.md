# Direkte AVARMA Home Assistant einbindung per Modbus integration

## Hardware
Man benötigt ein USB RS-485 Interface oder ein RS-485 TCP Gateway um mit der Wärmepumpe zu kommunizieren.

Beispiele für Interfaces:
https://www.waveshare.com/wiki/USB_TO_RS485

https://www.waveshare.com/product/rs232-to-eth-b.htm

Das Interface wird an die Schnittstelle COMM 3 der Wärmepumpe angeschlossen (A / B / GND).

## Home Assistant
In Home Assistant muss man die Register der WP per YAML konfigurieren.

Komplette YAMLs findet man z.B. hier: https://akkudoktor.net/t/avarma-wp-monoblock-r290/16194/218