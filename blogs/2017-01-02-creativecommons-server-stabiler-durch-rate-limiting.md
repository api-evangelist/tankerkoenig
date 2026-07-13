---
title: "creativecommons-Server: stabiler durch rate Limiting"
url: "http://blog.tankerkoenig.de/2017/01/creativecommons-server-stabiler-durch.html"
date: "2017-01-02"
author: "Unknown"
feed_url: "http://blog.tankerkoenig.de/feeds/posts/default"
---
Nachdem in letzter Zeit der creativecommons-Server einige Male durch sehr viele Anfragen zu stark belastet wurde, haben wir ein Rate-Limiting eingebaut. Durch die starke Belastung wurden die Antwortzeiten für alle Benutzer schlechter und manche Requests lieferten Fehlermeldungen. Wir gehen davon aus, dass die Probleme durch Konfigurationsfehler auf der Client-Seite auftraten.
