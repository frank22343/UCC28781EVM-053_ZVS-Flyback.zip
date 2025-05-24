# UCC28781EVM-053_ZVS-Flyback.zip

Das UCC28781EVM-053 ist ein Evaluierungsmodul (EVM) von Texas Instruments zur Demonstration eines klassischen Flyback-Konverters mit galvanischer Trennung. Es basiert auf dem UCC28781-Controller und eignet sich ideal für isolierte DC/DC-Anwendungen mit mittlerer Leistung.

<img width="413" alt="image" src="https://github.com/user-attachments/assets/ff9b1bb4-5b40-4d9b-8596-ab5068b728e4" />


Technische Eckdaten:
Topologie: Nicht-resonanter, klassischer Flyback-Konverter

Schaltfrequenz: ca. 100 kHz, primärseitig getaktet

Eingangsspannung: 12 V bis 60 V DC

Ausgangsspannung: 12 V DC, geregelt

Ausgangsstrom: Bis zu 3 A (36 W)

Galvanische Trennung: Ja, mittels Transformator

Regelung: Sekundärseitig über Optokoppler und TL431

Schutzfunktionen: Unter-/Überspannung, Kurzschluss, Überlast

Beschreibung und Funktionsweise:
Dieses EVM zeigt den Aufbau eines einfachen isolierten Flyback-Wandlers, wie er in vielen industriellen und embedded Anwendungen eingesetzt wird.
Die Regelung erfolgt über einen Optokoppler, der die Ausgangsspannung überwacht und eine präzise Rückkopplung zur Primärseite ermöglicht.
Ein TL431 auf der Sekundärseite dient dabei als Referenz- und Regelbaustein.

Die Schaltfrequenz von etwa 100 kHz wird vom UCC28781 erzeugt und je nach Lastsituation adaptiv angepasst. Der Transformator übernimmt dabei sowohl die Energieübertragung als auch die galvanische Trennung zwischen Primär- und Sekundärseite.

Besonderheiten:
Einfache, kostengünstige und robuste Flyback-Topologie

Breiter Eingangsspannungsbereich (ideal für variable DC-Quellen oder Vorspannungen)

Galvanisch getrennte Stromversorgung für nachgelagerte Systeme (z. B. Mikrocontroller, Sensorik, Kommunikation)

Hoher Wirkungsgrad durch optimierte Schaltzeiten und gut dimensionierten Transformator

Kompatibel mit industriellen Normen durch EMV-gerechtes Layout
