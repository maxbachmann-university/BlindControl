# Requirements blind control

## General Information

### Budget
The University has some Arduino UNO´s

### Team
* Maximilian Bachmann (@maxbachmann)
* Marvin Eisenmann (@leninja420)
* Florian Vetter (@floydsteam)

### Time
The Project has to be finished until: 8.3.18


## Project Requirements

Die Jalousiesteuerung soll eine Ansteuerung der Jalousien sowohl ein vollständiges Öffnen bzw. Schließen der Jalousien, als auch eine teilweise Öffnung der Jalousien (also z.B. ein Öffnen auf 40%) ermöglichen.

Es sollen verschiedene Möglichkeiten zur Ansteuerung implementiert werden. Konkret sind das für den Prototyp:
1) automatische Ansteuerung auf Basis von Sensorwerten. Für den Prototyp sollen ein Helligkeitssensor, sowie ein Windsensor eingebunden werden.
2) manuelle Ansteuerung basierend auf einer bestehenden Smarthome Plattform um die Steuerung komfortabel für alle Smart Home Geräte über eine Plattform zu ermöglichen
3) sprachbasierte Ansteuerung basierend auf dem offline Sprachassistenten Snips

Für den Prototyp soll die Gerätezahl möglichst gering gehalten werden, es sollen jedoch alle Funktionen ersichtlich sein.
Da im Rahmen des Projekts keine elektrische Jalousie zur Verfügung steht genügt es eine andere Komponente anzusteuern, deren Ansteuerung einer Jalousie nahe kommt. Die Implementierung soll in einer Art strukturiert sein, die eine einfache Einbindung unterschiedlicher Jalousien ermöglicht (z.B. über Schnittstellen der Hersteller bzw. Hardwarehacks). Der Stromverbrauch ist hierbei nicht wirklich relevant, da aufgrund des relativ hohen Stromverbrauchs der Jalousiemotoren ein Akkubetrieb nicht infrage kommt. 
Die Sensoren können für den Prototyp alle in einem Sensorgerät implementiert werden und müssen nicht getrennt aufgebaut werden. Anforderungen an die Sensorgeräte sind ein sehr niedriger Stromverbrauch, da die Geräte nur schlecht an eine Stromquelle angeschlossen werden können. Mindestbetriebszeit soll hierbei ein Jahr darstellen. Wie bei der Jalousiesteuerung soll die Implementierung eine problemlose Anbindung anderer Sensoren ermöglichen.



Requirements nach Standard:

Kategorie: F = Funktional, I = Interface, Q = Quality
Verifikationsmethode: S(imiliaris), I(nspection), R(eview), M(easurement), A(nalysis), T(est)

|ID|Text        |Kat.|VM|
|--|-------------------------------------------------------------------------------------------------|----|--|
|1|Das System soll die Position einer Jalousie zwischen 0% und 100% einstellen können|F|??|
|2|Der Sollwert für die Jalousieposition soll mit Home Assistant (Smarthome Plattform) manuell einstellbar sein|IF|??|
|2|Der Sollwert für die Jalousieposition soll mit MQTT(Message Queuing Telemetry Transport) Nachrichten einstellbar sein|IF|??|
|3|Der Sollwert für die Jalousieposition soll entsprechend von Sensorwerten einstellbar sein|IF|??|
|4|Das System soll aktuelle Sensorwerte als MQTT(Message Queuing Telemetry Transport) Nachricht ausgeben|IF|??|
|5|Das System soll die neue Jalousieposition als MQTT(Message Queuing Telemetry Transport) Nachricht ausgeben|IF|??|
|6|Aktuelle Sensorwerte sollen mit Homeassistant angezeigt werden können|IF|??|
|7|Die neue Jalousieposition soll mit Homeassistant angezeigt werden können|IF|??|
|8|Das Sensormodul soll netzunabhängig betrieben werden.|F|??|
|9|Die Batterie des Sensormoduls soll mindestens 1 Jahr überdauern|F|??|
|10|Die Batterie des Sensormoduls soll austauschbar sein|F|??|
|11|Das System soll 1 mal pro Sekunde aktualisiert werden|F||??|
|12|Das System (bis auf das Sensormodul) soll über eine externe Spannungsversorgung betrieben werden|F|??|
|13|Die aktuellen Sensorwerte sollen vom Sensormodul gemessen werden|IF|??|

