# RFID-Zutrittssystem

## Projektbeschreibung

Das RFID-Zutrittssystem soll den Zutritt mehrerer RFID-Transponder regeln. Dabei werden manchen Transpondern der
Zutritt gewährt und manchen wiederrum nicht.

* zweimaliges blinken: Zutritt verweigert
* dauerhaftes blinken:  Zutritt gewährt
* bei gewährtem Zutritt wird ein Servomotor angesteuert
* Textausgabe (z.B. Guten Tag Herr xy)

## Eingebundene Bibliotheken

* serielle Kommunikation **<SPI.h>**
* RFID-Bibliothek **<RFID.h>**
* Servo-Bibliothek **<Servo.h>**

## Optional

* schnelles und unaufwändiges hinzufügen neuer RFID-Transponder ins System
* schnelles und unaufwändiges entfernen alter RFID-Transponder aus dem System
