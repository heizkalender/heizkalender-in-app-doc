#  3. Gruppenvariablen

Gruppenvariablen definieren die Ressource, die mit dem Heizkalender gesteuert werden. Eine Gruppenvariable enthält die Aktoren, die angesteuert werden sollen und einige besondere Parameter. Die Aktoren sind typischerweise Thermostate, CCU Heizungsgruppen oder Schalter. Eine Gruppe kann ggf. auch nur aus einem Gerät bestehen. 

*Beispiele: Raume, Saal, Sitzungszimmer, Saal mit Flur und mit WC, Beregnungsventil, Saal-Belüftung.*

Gruppenvariablen werden in CCU Systemvariablen gespeichert: **HKG-xxxxx**

## Hinweise

Eine Gruppe sollte typischerweise alle Heizkörper-Thermostate eines Raumes zusammenfassen. Alternativ kann auf der CCU eine CCU-Heizungsgruppe erzeugt werden und diese in der Gruppenvariable hinterlegt werden.

Die Gruppe muss sortenrein geführt werden, also entweder Homematic Klassik oder Homematic IP. 

Man kann Aktoren mehrfach zuordnen. Das macht beispielsweise Sinn, wenn man Toiletten und Foyer zusammen mit anderen Räumen automatisch mit beheizen möchte. Dann fügt man jeder solcher Gruppe den Thermostat der Toilette und den des Foyers bei. Über solche Gruppen kann man beispielsweise auch ein ganzes Stockwerk oder Haus mit einem einzigen Befehl beheizen. 

Alle Thermostate einer Gruppe erhalten die gleichen Temperaturen und Schaltfunktionen. Aber an den meisten Thermostaten kann man einen Temperaturversatz einstellen, so dass die Toiletten durch die Einstellung des Thermostats kälter als die Räume gehalten werden können, also kälter als die Temperaturvorgabe für die Gruppe, z.B. bei Flur und Toiletten.

### Betrifft Varianten ChurchTools und ChurchDesk

Ein Problem ist, dass ChurchTools im Kalender derartige Gruppen nicht sauber abbilden kann. Also wenn ein Stockwerk in ChurchTools reserviert wird, sieht man das im Belegungsplan nicht bei den einzelnen Räumen des Stockwerks.

### Betrifft Varianten Google Kalender und Standard ICD (iCal)

Hier kann man frei definieren, z.B. Stockwerke, Raum-Gruppen.
