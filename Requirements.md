# Requirements blind control

##General Information

###Budget
The University has some Arduino UNO´s

###Team
Marvin Eisenmann
Florian 
Maximilian Bachmann

###Time
The Project has to be finished until:


##Project Requirements

Die Jalousiesteuerung soll eine Ansteuerung der Jalousien sowohl ein vollständiges Öffnen bzw. Schließen der Jalousien, als auch eine teilweise Öffnung der Jalousien (also z.B. ein Öffnen auf 40%) ermöglichen.

Es sollen verschiedene Möglichkeiten zur Ansteuerung implementiert werden. Konkret sind das für den Prototyp:
1) automatische Ansteuerung auf Basis von Sensorwerten. Für den Prototyp sollen ein Helligkeitssensor, sowie ein Windsensor eingebunden werden.
2) manuelle Ansteuerung basierend auf einer bestehenden Smarthome Plattform um die Steuerung komfortabel für alle SMart Home Geräte über eine Plattform zu ermöglichen
3) sprachbasierte Ansteuerung basierend auf dem offline Sprachassistenten Snips

Für den Prototyp soll die Gerätezahl möglichst gering gehalten werden, es sollen jedoch alle Funktionen ersichtlich sein.
Da im Rahmen des Projekts keine elektrische Jalousie zur Verfügung steht genügt es eine andere Komponente anzusteuern, deren Ansteuerung einer Jalousie nahe kommt. Die Implementierung soll in einer Art strukturiert sein, die eine einfache Einbindung unterschiedlicher Jalousien ermöglicht (z.B. über Schnittstellen der Hersteller bzw. Hardwarehacks). Der Stromverbrauch ist hierbei nicht wirklich relevant, da aufgrund des relativ hohen Stromverbrauchs der Jalousiemotoren ein Akkubetrieb nicht infrage kommt. 
Die Sensoren können für den Prototyp alle in einem Sensorgerät implementiert werden und müssen nicht getrennt aufgebaut werden. Anforderungen an die Sensorgeräte sind ein sehr niedriger Stromverbrauch, da die Geräte nur schlecht an eine Stromquelle angeschlossen werden können. Mindestbetriebszeit soll hierbei ein Jahr darstellen. Wie bei der Jalousiesteuerung soll die Implementierung eine problemlose Anbindung anderer Sensoren ermöglichen.
test


 
