#  3. Außentemperatur

In diesem Abschnitt finden sie Funktionen, um Ihre CCU so einzurichten, dass Sie die Außentemperatur ermittelt und dem Heizkalender zu temperaturabhängigen Steuerung verfügbar macht.

## Dienst

Der Heizkalender unterstützt die folgenden Optionen, um die Ausentemperatur auszulesen:

### Deutscher Wetterdienst (DWD)

Bestimmen sie in Abschnitt *DWD Parameter* welche DWD Station ausgelesen werden soll. Es wird die Tageshöchsttemperatur-Prognose ausgelesen und genutzt.


### Lokaler Sensor (Homematic)

Wählen Sie den gewünschten Sensor aus. In der Auswahlliste werden nur die Geräte angezeigt, die zuvor auf üblichem Homematic-Weg bei der CCU angelernt wurden.


## CCU Programm installieren

Wählen Sie diese Aktion, um das zugehörige Programm auf die CCU zu übertragen. Das CCU Programm aktualisiert die Außentemperatur-Variable [HK2-Aussentemperatur] periodisch.

Je nach ausgewählter Option wird folgendes CCU Programm gespeichert:

- **HKP-A-Temp.finder-DWD**: Deutscher Wetterdienst

- **HKP-A-Temp.finder-Sensor**: Sensor (Homematic)



## Außentemperatur-Variable aktualisieren

Die CCU aktualisiert die Außentemperatur-Variable [HK2-Aussentemperatur] periodisch. Zu Testzwecken kann das CCU Programm hier auch unmittelbar ausgeführt werden.
