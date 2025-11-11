<a name="readme-top"></a>
# Grundlagen zur WebEntwicklung
Author: Daniel Pöttler <br>
LBS Eibiswald | 3aAPC

1 Aufgabenstellung - Sicherheit und Maßnahmen in der WebEntwicklung<br>

## Überblick

> Browser stellt Anfrage
Der Benutzer gibt eine Adresse ein (z. B. google.com).
→ Der Browser schickt eine Anfrage an den Webserver.
Webserver empfängt die Anfrage
>
> Der Server prüft, welche Daten oder Webseite gebraucht wird.
Webserver sendet Antwort
>
> Er schickt HTML, CSS, Bilder, usw. zurück an den Browser.
Browser zeigt die Seite an
Der Browser baut daraus die Webseite und zeigt sie dem Benutzer
>
> Der Server prüft, welche Daten oder Webseite gebraucht wird.
Webserver sendet Antwort
>
> Er schickt HTML, CSS, Bilder, usw. zurück an den Browser.
Browser zeigt die Seite an
Der Browser baut daraus die Webseite und zeigt sie dem Benutzer

## Sicherheitsrisiken von Webanwendungen
> **Sicherheitsrisiken von Webanwendungen**
> **Phishing:** Nutzer werden auf gefälschte Webseiten gelockt, um Passwörter oder Daten zu stehlen.  
> **Datendiebstahl:** Angreifer brechen in Systeme ein und stehlen persönliche oder vertrauliche Daten.  
> **SQL Injection:** Schadbefehle werden in Datenbankabfragen eingeschleust, um Daten zu lesen, zu löschen oder zu verändern.  
> **Cross-Site-Scripting (XSS):** Angreifer fügen schädliches JavaScript auf Webseiten ein, um Nutzer zu manipulieren oder Cookies zu stehlen.  
> **Session-Hijacking:** Sitzungsdaten wie Cookies werden gestohlen, damit der Angreifer sich als Nutzer ausgeben kann.  
> **DoS/DDoS:** Server wird mit extrem vielen Anfragen überlastet und ist nicht mehr erreichbar.

## Maßnahmen zum Schutz

> **HTTPS/Verschlüsselung:** Daten werden sicher übertragen und können nicht einfach mitgelesen werden.  
> **Multifaktor-Authentifizierung:** Login ist sicherer, da zusätzlich zum Passwort ein zweiter Faktor benötigt wird.  
> **Sanitizing & Prepared Statements:** Sorgen dafür, dass Benutzereingaben kein Schadcode sind → Schutz vor SQL Injection.  
> **Passworthashing & sichere Speicherung:** Passwörter werden nicht im Klartext gespeichert und bleiben bei einem Angriff geschützt.  
> **Firewalls & Rate-Limiting:** Blockieren gefährliche Anfragen und stoppen DoS-Versuche.  
> **Regelmäßige Updates:** Sicherheitslücken in Software und Server werden geschlossen.

## Screenshot der Entwicklungsumgebung
(Ist ein Versuch der Anzeige von Bildern)
[![Screen Shot][product-screenshot]](https://example.com)

[product-screenshot]: images/entwicklungsumgebung.png