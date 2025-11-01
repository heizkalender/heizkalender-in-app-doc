#  2. Heizungssteuerung

Dieses Programmteil (Skript 2) steuert die Aktoren, also die Geräte die aus dem Homematic-System mit dem Heizkalender verbunden sind. Das geschieht wetterabhängig, mit Unterschiedlichen Vorlauf- und Ausschalt-Zeiten.

Im Folgenden werden die Parameter, die zu ihrem Haus passen, eingegeben. Im Zweifel verwenden Sie zunächst die vorgeschlagenen Standardwerte. Im Laufe der Zeit und mit ihrer Erfahrung können Sie jederzeit Die Parameter anpassen.

## Allgemeine Konfiguration

Tragen Sie hier die Parameter der Heizungssteuerung ein. Die Werte werden in der CCU in Systemvariablen gespeichert.

## CCU Programm installieren

Wählen Sie diese Aktion im Anschluss an die Eingabe der allgemeinen Konfiguration, um das zugehörige Programm auf die CCU zu übertragen. Das CCU Programm überprüft im 5-Minuten Intervall die aktuelle Schaltliste (erzeugt durch das Kalender-Programm) und steuert die Heizungsaktoren und/oder Schalter entsprechend.  

Die Heizungssteuerung wird als CCU Programm gespeichert: **HKP-S2**

## Heizungssteuerung aktualisieren

Die CCU steuert die Heizungsaktoren und/oder Schalter in einem 5-Minuten Intervall. Zu Testzwecken kann das CCU Programm hier auch unmittelbar ausgeführt werden.
