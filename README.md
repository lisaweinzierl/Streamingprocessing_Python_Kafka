# Streamingprocessing_Python_Kafka

## Excersise 1:
Go to https://opensensemap.org/ and read the introduction for the sensor-api: https://docs.opensensemap.org/ 

1) Create a http request from your jupyter notebook to the url

2) Print the sensor data in a static way

3) Try to create the request dynamic

4) Try out the date format

WLI-Solution: Excersise_OpenSenseMap_v2

## Excersise 2:

1) Bereitstellen der Daten
     1.1) download der openbeer Datenbank von: https://openbeerdb.com/, "openbeerdb_csv.zip" (Man darf sich den Link vorher zusammenbauen. Die Idee ist jedoch, dass nach dem publizieren eines Notebooks/Code dieser Standalone ist und man keine weiteren Interkationen vom benutzer benötigt)
     1.2) unzip und einlesen der csv in python

2) Einlesen der Daten in eine Klasse die Datenverarbeitung auf python ermöglicht
     2 A.1) Welches Paket ist gut geeignet und warum?
     2 A.2) Einlesen der Daten in dieses Paket.
     2 A.3) Erstellen einer "Qualitativen Zusammenfassung" zu den Daten.

3) Einlesen der Daten in eine lokalen Datenbank
     2 B.1) Welche Datenbank ist gut geeignet und warum?
     2 B.2) Einlesen der Daten in diese Datenbank.
     2 B.3) Erstellen einer "Qualitativen Zusammenfassung" zu den Daten.

4) Fragen auf den Daten

5) Visualisierung der Daten
     4.1) Welche Pakete gibt es hier und was sind die Unterschiede?
     4.2) Was ist ein gutes Datendesiugn für die Visualisierung, und warum?

6) Script vs. Class Design
     5.1) If you did it as a script do the exercises also in a class design.
     5.2) If you did it as a class design, do the exercises als in a script design. (externalize the repetitive stuff in functions)
     5.3) A non primitive function needs proper testing ;-)
     
7) Abfrage Strategien
     6.1) Welches Format ist geeignet um die Daten so abzulegen, dass man sie effizient abrufen kann (die gesamten Daten).
     6.2) Welche interne Struktur würde man wählen damit man bei der Eingabe von einem Alkohol Wert möglichst schnell und effizient die Liste der Hersteller herausgeben kann?
