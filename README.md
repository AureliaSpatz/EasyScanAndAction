# EasyScanAndAction
Aktionen/Aufgaben/Informationen per QR-Code übertragen und ausführen

## In aller Kürze:
Mittels einer App für Android und iOS können QR-Codes erstellt und gescannt werden.
Die enthaltenen Informationen triggern auf der scannenden Seite halb-/automatische Aktionen, wie zum Beispiel den Versand einer vorformatierten E-Mail an einen übertragenenen Empfänger.
Mit der App können sowohl QR-Codes erstellt als auch gelesen und ausgeführt werden.

Entwickelt werden soll die App in ihrer Basisfunktionalität im OL Civic Data Lab Hackathon [1]. Das Protokoll, also welche Daten/Aktionen im QR-Code ausgetauscht werden können, ist noch nicht festgelegt und gerade dafür bietet sich ein Hackathon mit vielen Teilnehmern aus verschiedensten Fachrichtungen und mit unterschiedlichsten Interessen an, um einen schönen Strauß an Anwendungsmöglichkeiten zu bekommen.

## Szenario 1:
Aktuell müssen - zum Beispiel in Restaurants und bei Frisören (Geschäft) - zur Corona-Kontaktnachverfolgung bei jedem Besuch die Kontakdaten des Kunden aufgenommen und für wenige Wochen aufbewahrt werden.
Bis auf kleine Unterschiede im Umfang der erhobenen Daten findet immer der gleiche Vorgang statt.
Mit der App kann dieser Vorgang sowohl für den Kunden, als auch für das Geschäft wesentlich komfortabler gestaltet werden:
Das Geschäft erstellt mit der App einen QR-Code, der folgendes enthält:
- Eine Aktions-ID (Datenabfragen und Senden)
- Umfang der gewünschten Kontaktdaten
- E-Mail-Adresse, an die die Kontaktdaten geschickt werden sollen
Der QR-Code wird als PDF erstellt, ausgedruckt und für den Kunden scannbar am Eingangstresen oder auf den Tischen oder in den Speisekarten angebracht.

Der Kunde kann den QR-Code dann mit dieser App scannen. Daraufhin wird die Aktions-ID interpretiert und die gewünschten Daten in einem Formular abgefragt. Nur beim ersten Mal müssen die Daten eingegeben werden. Im nächsten Geschäft oder beim zweiten Besuch werden die Daten dann schon automatisch vorausgefüllt.
Mit einem Klick auf "Absenden" wird dann eine entsprechend formatierte und gefüllte Mail an die übergebene E-Mail-Adresse gesendet.

Papier ist damit nicht mehr nötig und die Datenerfassung geht wesentlich schneller und einfacher.

## Szenario 2:
Einmalzugang nach Bezahlung. Beispielsweise zu einem Fitnessstudio.\
Der Kunde kann im Fitnessstudio einen QR-Code scannen, über den in diesem Fall ein Bezahlvorgang angezeigt und dann mittels der App gestartet/erledigt werden kann. Sobald das Fitnessstudio den Geldeingang registriert hat, wird das Drehkreuz bzw. die Tür geöffnet.\
In diesem Szenario ist die App allein nicht ausreichend, da das Drehkreuz bzw. der Türöffner vom Fitnessstudio angesteuert werden muss.

## QR-Code Protokoll (mögliche enthaltene Daten)
* Aktions-ID
* Kontaktdaten, die abgefragt werden sollen
* E-Mail-Adresse des Geschäfts
* Name des Geschäfts
* URL zur Speisekarte
* URL zur Getränkekarte
* WLAN-Zugangsdaten 

## Technik
QT/QML [2] \
qzxing [3] 

## Lizenz
Es wird eine OpenSource-Lizenz, muss noch entschieden werden

[1] https://hackathon.kreativitaet-trifft-technik.de/ \
[2] https://www.qt.io/, https://doc.qt.io/qt-5/qtqml-index.html \
[3] https://github.com/ftylitak/qzxing 

## Download

Derzeit nur eine Hello-Hackathon-App 

https://www.jw78.de/download/esaa.apk

## Kontakt
Jens Wienöbst \
esaa@jw78.de

