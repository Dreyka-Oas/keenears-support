# KeenEars support

English first, français plus bas.

KeenEars is a Fabric mod for Minecraft servers. Every mob hears the sounds the server plays. Monsters walk over to check where a noise came from, animals and villagers turn their head toward it and run from loud ones, and walls change what carries: by default a wool enclosure stops a sound the way it does for the Warden. The rule runs on the server alone, so players install nothing to join.

This repository holds no code. It is the place to report a problem or ask a question about the mod, and nothing else.

## Reporting a bug

Open an issue and pick the bug form. It asks for the game and loader versions, the mod version, what you expected, what happened, the steps to reproduce it and the lines of `latest.log` around it. A report with those lines gets answered much faster than one without them.

Before you write, check three things. The mob may be excluded, by the `excludedMobs` setting or the tag `keenears:deaf`. Its reaction may be set to `none` for its kind. And a mob already walking its own path keeps it, then goes to the noise if the path ends within 3 seconds. Settings live in OasCore and in `config/oas/keenears/keenears.json`. Setting `probeIntervalTicks` above 0 makes the server log one line per world about what hearing did, which is worth attaching.

## What is not a bug

A monster that does not answer another monster's footsteps is the default, `monstersHearMonsters` turns it on. An animal that only turns its head at a footstep and runs from an explosion is the default too. A mob that hears nothing through a wool wall is the Warden rule at work. Sounds the server never plays, such as mining hits, ambience and music, are not heard at all.

## Français

KeenEars est un mod Fabric pour serveurs Minecraft. Tous les mobs entendent les sons que le serveur joue. Les monstres vont voir d'où vient le bruit, les animaux et les villageois tournent la tête vers lui et s'éloignent des bruits forts, et les murs changent ce qui porte : par défaut une enceinte de laine arrête un son comme pour le Warden. La règle tourne côté serveur seulement, donc les joueurs n'installent rien pour se connecter.

Ce dépôt ne contient aucun code. On y signale un problème ou on y pose une question sur le mod, rien d'autre.

### Signaler un bug

Ouvrez un ticket et choisissez le formulaire de bug. Il demande les versions du jeu et du chargeur, la version du mod, ce que vous attendiez, ce qui s'est passé, les étapes pour le reproduire et les lignes de `latest.log` autour du problème. Un signalement avec ces lignes reçoit une réponse bien plus vite.

Avant d'écrire, vérifiez trois choses. Le mob est peut-être exclu, par le réglage `excludedMobs` ou l'étiquette `keenears:deaf`. Sa réaction est peut-être sur `none` pour son espèce. Et un mob qui suit déjà son propre chemin le garde, puis va vers le bruit si le chemin se termine dans les 3 secondes. Les réglages sont dans OasCore et dans `config/oas/keenears/keenears.json`. Mettre `probeIntervalTicks` au-dessus de 0 fait écrire au serveur une ligne par monde sur ce que l'ouïe a fait, utile à joindre.

### Ce qui n'est pas un bug

Un monstre qui ne répond pas aux pas d'un autre monstre, c'est le comportement par défaut, `monstersHearMonsters` l'active. Un animal qui tourne seulement la tête devant un pas et fuit devant une explosion, c'est aussi le comportement par défaut. Un mob qui n'entend rien à travers un mur de laine, c'est la règle du Warden. Les sons que le serveur ne joue jamais, comme les coups de minage, l'ambiance et la musique, ne s'entendent pas du tout.
