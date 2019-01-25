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

Requirements nach Standard:

Kategorie: F = Funktional, IF = Interface, Q = Quality</br>
Verifikationsmethode: S(imiliaris), I(nspection), R(eview), M(easurement), A(nalysis), T(est)

|ID|Text        |Kat.|VM|
|--|-------------------------------------------------------------------------------------------------|----|--|
|1|Das System soll modular in einen Regler, ein Sensormodul und eine Aktorsteuerung aufgeteilt sein|F|T|
|2|Das System soll die Position einer Jalousie zwischen 0% und 100% einstellen können|F|T|
|3|Der Sollwert für die Jalousieposition soll mit Home Assistant (Smarthome Plattform) manuell einstellbar sein|IF|T|
|4|Der Sollwert für die Jalousieposition soll eine Schnittstelle zur manuellen Einstellung der Jalousieposition bieten sein|IF|T|
|5|Der Sollwert für die Jalousieposition soll entsprechend von Sensorwerten einstellbar sein|IF|T|
|6|Das System soll aktuelle Sensorwerte ausgeben|IF|T|
|7|Das System soll die neue Jalousieposition ausgeben|IF|T|
|8|Aktuelle Sensorwerte sollen mit Homeassistant angezeigt werden können|IF|T|
|9|Die neue Jalousieposition soll mit Homeassistant angezeigt werden können|IF|T|
|10|Das Sensormodul soll netzunabhängig betrieben werden.|F|I|
|11|Die Batterie des Sensormoduls soll mindestens 1 Jahr überdauern|F|T|
|12|Die Batterie des Sensormoduls soll austauschbar sein|F|I|
|13|Das System soll 1 mal pro Sekunde aktualisiert werden|F||T|
|14|Das System (bis auf das Sensormodul) soll über eine externe Spannungsversorgung betrieben werden|F|T|
|15|Die aktuellen Sensorwerte sollen vom Sensormodul gemessen werden|IF|T|


