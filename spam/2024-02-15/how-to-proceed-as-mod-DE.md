# Wie als Moderator:In mit dieser Liste und dem Spam umzugehen ist

## Aufgabe 1: Liste Durchgehen

Du musst auf die Instanz, wie in der Liste beschrieben, gehen und sehen ob auf der öffentlichen lokalen timeline sichtbar ist das der Spam noch auftritt.

https://instancedomain.tld/public/local 
(*ersetze "instancedomain.tld" mit der Domain der ggf. Spam betroffenen Instanz*). 

### Falls dort Spam ist

Wenn dort noch offensichtlich Spam geposted wird dann soll die Instanz stummgeschaltet werden. Gehe dafür auf:

https://troet.cafe/admin/domain_blocks/new 
(*ersetze troet.cafe mit der Instanz-Domain die du moderierst*)

Trage folgendes ein:

- **Domain:** instancedomain.tld 
  
  (*hier die Instanz mit gefundenen Spam-Inhalten eintragen*)
- **Schweregrad:** Stummschaltung 
  
  (*ganz wichtig hier NICHTS anderes als Stummschaltung eintragen*)
- **Mediendateien ablehnen:** ☑ / CHECK 
  
  (*der Spam benutzt oftmals Bilder, Mediendateien müssen abgelehnt werden*)
- **Meldungen ablehnen:** ☐ / NICHT CHECK 
  
  (*es werden keine falschen Meldungen bisher von den Spammern gesendet*)
- **Domain-Name verschleiern:** ☐ / NICHT CHECK 
  
  (*die Domain ist bei Spam meistens nicht schädlich*)
- **Private bzw. nicht-öffentliche Notiz:** „February 15th 2024 Fediverse Spam Attacks | https://mastodon.de/@ErikUden/111940301222380638“ 
  
  (*es soll intern notiert werden wieso dieser Block stattfand*)
- **Öffentliche Notiz:** „Spam (2024-02-15)“ 
  
  (*es soll extern klargestellt werden wieso dieser Block stattfand*) 



Das wars, dann auf zur nächsten Instanz!

### Falls dort kein Spam ist

Wenn du auf der öffentlich-lokalen Timeline der gemeldeten Instanz kein Spam mehr findest meldest du den Link zurück an den Listen-Ersteller (*Erik Uden*). Checke zudem ob der alte Spam bereits gelöscht wurde (*also auf der lokalen öffentlichen Timeline bis vor 3 Tagen keiner dieser Spam Accounts / Posts gefunden wird*) und gebe diese Info in der Rückmeldung mit. 

### Falls du die öffentliche lokale Timeline nicht sehen kannst weil dies limitiert ist

Erstelle einen Account auf der Plattform und gucke dann die öffentliche lokale Timeline an. 

### Falls du die Instanz nicht erreichen kannst / sie offline ist

Melde die Instanz mit diesen Infos zurück an den Listen-Ersteller (*Erik Uden*). 

<br/>

<br/>

## Aufgabe 2: Reports Durchgehen

Alle Meldungen die und erreichen bedeuten das jemand von unseren Instanzen den Spam abbekommen hat. Es reicht nicht die gemeldeten Accounts lediglich zu sperren, deren Instanz-Domain muss notiert werden, abgeglichen werden mit der bisherig existierenden Liste, und wenn es eine neue Domain ist dann muss sie zur Liste hinzugefügt werden. Benachrichtige den Listen-Ersteller (*Erik Uden*) oder trage diese eigenständig in die Liste ein. 

Falls es eine Meldung lokal oder extern von einen unserer Accounts ist und der Spam unsere Instanz doch wieder erreicht hat, dann ist das ein Notfall und kontaktiere sofortig die Admins. 

## Aufgabe 3: Liste Erstellen und Verteilen

Wenn das fertig ist exportierst du die Liste als CSV-Datei gibst sie dem Listen-Ersteller (*Erik Uden*) oder benachrichtigst ihn lediglich das du fertig bist. 
Dieser bereinigt die Liste sodass nur die 2024-02-15 Fedi Spam Attacks Instanzen drauf sind (*dafür sind die internen und externen Notizen sehr hilfreich*) und läd diese
 daraufhin im GitHub Repository hoch und importiert sie auf die anderen Instanzen (*muenchen.social, mastodon.de*). 

## Wichtig

Wenn ein lokaler Spam-Bot sich erstellt auf troet.cafe, muenchen.social, oder mastodon.de benachrichtige bitte sofort die Admins (*Erik Uden, Nick, Martin*). Das wäre nämlich ein Notfall. 