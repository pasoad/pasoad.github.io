---
published: true
layout: post
---

## Problème de connexion réseau avec Windows 11

J'ai récemment eu des soucis de connexion internet avec Windows 11.

En effet, du jour au lendemain, Impossible d’accéder à un site Internet et d’effectuer une mise à jour de windows (Je précise que tous mes autres appareils n’avait aucun problèmes avec le réseau). 

Après avoir redémarré mon ordinateur ainsi que ma box, toujours rien… j'ai trouvé la solution sur le site [malekal](https://www.malekal.com/pas-internet-windows-11-probleme-internet/).

Il fallait simplement changer les paramètres DNS de Windows.

Dans Paramètres/Réseau et Internet/Ethernet (ET/OU WiFi)

Ensuite il faut sélectionner IPv4 et remplir le champ "DNS préféré"

![Capture d'écran résumant la procédure]({{site.baseurl}}/_posts/Capture d'écran 2023-08-13 221953.png)

J'ai choisi d'utiliser le serveur DNS de chez CloudFlare : 1.1.1.1