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
     * download der openbeer Datenbank von: https://openbeerdb.com/, "openbeerdb_csv.zip" (Man darf sich den Link vorher zusammenbauen. Die Idee ist jedoch, dass nach dem publizieren eines Notebooks/Code dieser Standalone ist und man keine weiteren Interkationen vom benutzer benötigt)
     * unzip und einlesen der csv in python

2) (oder 2A) Einlesen der Daten in eine Klasse die Datenverarbeitung auf python ermöglicht
     * Welches Paket ist gut geeignet und warum?
     * Einlesen der Daten in dieses Paket.
     * Erstellen einer "Qualitativen Zusammenfassung" zu den Daten.

2) (oder 2B) Einlesen der Daten in eine lokalen Datenbank
     * Welche Datenbank ist gut geeignet und warum?
     * Einlesen der Daten in diese Datenbank.
     * Erstellen einer "Qualitativen Zusammenfassung" zu den Daten.

3) Fragen auf den Daten
      * Was ist der durschnittliche Alkoholgehalt der produzierten Biere nach Produktionsland?
      * Wie viele Brauereien gibt es pro Kontinent/Land/Stadt? Gibt es etwas auffälliges?
      * Wieviele Bierstile braut eine Braurei im Durchschnitt? Wieviele sind es pro Land?
      * Was ist der Median des Alkoholgehalts?
      * Welcher Bierstil ist hauptsächlich in welchem Land zu finden?

4) Visualisierung der Daten
     * Welche Pakete gibt es hier und was sind die Unterschiede?
     * Was ist ein gutes Datendesiugn für die Visualisierung, und warum?

5) Script vs. Class Design
     * If you did it as a script do the exercises also in a class design.
     * If you did it as a class design, do the exercises als in a script design (externalize the repetitive stuff in functions)
     * A non primitive function needs proper testing ;-)
     * Wenn du Zeit hast, mache einen super chart der mich vom Hocker haut ;-)
     
     
6) Abfrage Strategien
     * Welches Format ist geeignet um die Daten so abzulegen, dass man sie effizient abrufen kann (die gesamten Daten).
     * Welche interne Struktur würde man wählen damit man bei der Eingabe von einem Alkohol Wert möglichst schnell und effizient die Liste der Hersteller herausgeben kann?
