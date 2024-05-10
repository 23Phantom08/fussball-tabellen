###### Fussball-Tabellen

Hier entsteht eine Fussball Tabellen Auswahl für Verschiedene Ligen und Meisterschaften.
Es wird über ESPN abgerufen und ist immer aktuell.

Zuallererst erstellt Ihr euch in der config eine neue Datei und nennt sie "sensor.yaml"(sollte die Datei bei euch noch nicht vorhanden sein)
Danach geht Ihr in die config.yaml und erstellt euch "sensor: !include sensor.yaml".
Damit kann auf die sensor.yaml Datei zugegriffen werden und die gewünschten Ligen und Meisterschaften in sensor.yaml einfügen und speichern nicht vergessen.
Unter Entwicklerwerkzeuge die config prüfen und Home Assistant neu starten.

Um euch die Liga Tabelle zu erstellen braucht ihr noch die flex-table-card,diese könnt ihr von HACS downloaden (wie man HACS installiert findet ihr überall online).
Wenn ihr die flex-table-card habt dann kopiert Ihr euch den Liga Tabellen code und geht auf Karte hinzufügen, wählt manuell aus und kopiert den Liga Tabellen code rein,ändert noch eure gewünschte Liga,den Namen der Liga wenn gewünscht und fertig.
