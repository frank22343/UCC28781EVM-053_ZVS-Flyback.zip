# UCC28781EVM-053_Flyback_Konverter

Das UCC28781EVM-053 ist ein Evaluierungsmodul (EVM) von Texas Instruments zur Demonstration eines klassischen Flyback-Konverters mit galvanischer Trennung. Es basiert auf dem UCC28781-Controller und eignet sich ideal für isolierte DC/DC-Anwendungen mit mittlerer Leistung.



![Screenshot 2025-05-24 213704](https://github.com/user-attachments/assets/a463d7a9-982a-49d7-87db-df38593c467d)





# Technische Eckdaten:
Topologie: Nicht-resonanter, klassischer Flyback-Konverter

Schaltfrequenz: ca. 100 kHz, primärseitig getaktet

Eingangsspannung: 12 V bis 60 V DC

Ausgangsspannung: 12 V DC, geregelt

Ausgangsstrom: Bis zu 3 A (36 W)

Galvanische Trennung: mittels Transformator

Regelung: Sekundärseitig über Optokoppler und TL431

Schutzfunktionen: Unter-/Überspannung, Kurzschluss, Überlast


# Beschreibung und Funktionsweise:

Dieses EVM zeigt den Aufbau eines einfachen isolierten Flyback-Wandlers, wie er in vielen industriellen und embedded Anwendungen eingesetzt wird.
Die Regelung erfolgt über einen Optokoppler, der die Ausgangsspannung überwacht und eine präzise Rückkopplung zur Primärseite ermöglicht.
Ein TL431 auf der Sekundärseite dient dabei als Referenz- und Regelbaustein.

Die Schaltfrequenz von etwa 100 kHz wird vom UCC28781 erzeugt und je nach Lastsituation adaptiv angepasst. Der Transformator übernimmt dabei sowohl die Energieübertragung als auch die galvanische Trennung zwischen Primär- und Sekundärseite.


<img width="631" alt="image" src="https://github.com/user-attachments/assets/463cf008-dd87-479f-9416-23529d498015" />

