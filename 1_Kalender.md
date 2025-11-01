#  1. Kalender

In diesem Abschnitt finden sie Funktionen, um Ihre CCU so einzurichten, dass Sie sich mit Ihrem bevorzugen Online-Kalender verbindet, daraus Belegungspläne ausliest und eine Schaltliste für Thermostate und Schalter zu erzeugen.

## Dienst

Der Heizkalender unterstützt die folgenden Dienste, um Raumbelegungspläne aus einem Online-Kalender auszulesen:

- ChruchTools API
- ChurchDesk ICS
- Google Calendar API
- Standard ICS (iCal URL)

Wir empfehlen **Standard ICS** nur dann zu verwenden, wenn die spezialisierten Dienste in Ihrem Szenario nicht genutzt werden.

## Zugangsdaten

Tragen Sie hier die Zugangsdaten zu Ihrem Kalender-Dienst ein. Die Zugangsdaten werden in der CCU in Systemvariablen gespeichert.

## CCU Programm installieren

Wählen Sie diese Aktion im Anschluss an die Eingabe der Zugangsdaten, um das zugehörige Programm auf die CCU zu übertragen. Das CCU Programm verbindet sich alle 30 Minuten mit dem Online-Kalender, erfasst den Raumbelegungsplan und erstellt daraus eine Schaltliste. (CCU Systemvariable: **HK1-Schaltliste**).

Die Kalenderintegration wird als CCU Programm gespeichert:

- **HKP-CT**: ChurchTools

- **HKP-ICS-CD**: ChurchDesk

- **HKP-GK**: Google Calendar

- **HKP-ICS**: Standard iCal


## Schaltliste aktualisieren

Die CCU aktualisiert die Schaltliste automatisch alle 30 Minuten. Zu Testzwecken kann das CCU Programm hier auch unmittelbar ausgeführt werden.
