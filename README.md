# Beschreibung
Der Logikbaustein setzt einen User Status über die Divera API. Es besteht die Möglichkeit einen zuvor definierten Status per Trigger zu setzen oder eine ID an den Eingang „Status ID“ zu senden um somit flexibel einen Status setzen zu können.

Link zur Divera API Dokumentation: https://api.divera247.com/?urls.primaryName=api%2Fv1#/E

## Eingänge

E1 Ein/Aus - Hiermit wird der Baustein aktiviert, beim Triggern wird der Status der am Eingang E3 anliegt erneut gesendet.

E2 API KEY - Hier müsst ihr euren eigenen Benutzer API Key angeben den ihr in euren Accounteinstellungen findet (Einstellungen/Debug)

E2 Status ID - Trifft an dem Eingang Zahl ein die einem in Divera angelegten Status gleicht wird dieser status gesendet. Der Status wird ab „1“ aufwärts gezählt. Zb. 1 = Verfügbar, 2 = nicht Einsatzbereit etc…..

## Ausgänge

A1 Status - Hier wird eine "1" ausgegeben wenn das senden des Status erfolgreich war.

A1 Debug - An diesem Ausgang werden Fehler falls vorhanden ausgegeben.
