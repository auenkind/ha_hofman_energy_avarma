# AVARMA Home Assistant einbindung per ESPHome

## Hardware
Man benötigt einen ESPHome kompatiblem Mikrocontroller mit RS-485 Interface.

Das Interface wird an die Schnittstelle COMM 3 der Wärmepumpe angeschlossen (A / B / GND).

## ESPHome

Die Komponente [hofman_energy_avarma](https://github.com/auenkind/esphome/tree/dev/esphome/components/hofman_energy_avarma) muss als external_component in die config eingebunden werden. 

YAML-Beispiele in der [README](https://github.com/auenkind/esphome/blob/dev/esphome/components/hofman_energy_avarma/README.md) der Komponente.

Sollte man den COMM 3 nicht verwenden können kann der ESP auch parallel zum Display angeschlossen werden, dann muss aber der passive_mode aktiviert werden. In der README befindet sich auch dazu ein Beispiel.