Digitales IP-Forensik-Toolkit
Dieses Web-basierte Tool ermöglicht die detaillierte Analyse einer IP-Adresse durch die Integration von Geolocation- und RDAP/WHOIS-Daten. Es bietet eine interaktive Karte, erweiterte Informationsanzeigen sowie eine IP-Historie-Funktion mit Export- und Löschmöglichkeiten.

Funktionen
IP-Eingabe & Validierung: Überprüfung des IP-Formats (IPv4/IPv6).
Geolocation-Details: Anzeige von Land, Stadt, Region, ISP, Organisation, Zeitzone, Netzwerkname, Koordinaten.
Interaktive Karte: Darstellung des Standorts mit Leaflet.js, zoombar und klickbar.
RDAP/WHOIS-Daten: Erweiterte Informationen wie Registrar, Status, Netzwerkname, Abuse-Email, Port 43, Kontaktinformationen (Name, Email, Telefon, Adresse).
IP-Historie: Speicherung der eingegebenen IPs in LocalStorage, Anzeige der Historie mit Klickmöglichkeit zur erneuten Abfrage.
Export & Löschen: Exportiere die IP-Historie als Textdatei oder lösche sie.
Technische Details
Frontend: HTML, Tailwind CSS, JavaScript
Karten: Leaflet.js mit OpenStreetMap
Datenquellen:
Geolocation: ipwhois.app API
RDAP: rdap.org API
Nutzung
IP-Adresse in das Eingabefeld eingeben.
Auf "Starten" klicken oder Enter drücken.
Die Ergebnisse werden in den Bereichen Geolocation, Karte, RDAP und IP-Historie angezeigt.
Historie kann exportiert oder gelöscht werden.
Hinweise
Die API-Daten sind öffentlich und kostenlos, daher kann es gelegentlich zu Verzögerungen oder unvollständigen Daten kommen.
Das Tool ist ideal für IT-Forensiker, Sicherheitsanalysten und alle, die eine schnelle IP-Analyse benötigen.
Lizenz
Dieses Projekt steht unter MIT License.

