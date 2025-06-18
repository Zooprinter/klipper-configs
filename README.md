🤖 Configurations Klipper de Zooprinter
 

Bienvenue ! 👋 Ce dépôt contient mes configurations Klipper personnelles, optimisées pour mes imprimantes 3D. Chaque imprimante fonctionne sur son propre serveur Klipper, ce qui explique pourquoi chaque dossier est entièrement autonome.

🖨️ Mes Imprimantes
🔥 Ender 3 V3 SE
(Pensez à ajouter une belle photo de votre imprimante, à l'héberger quelque part et à mettre le lien ici !)

Cette configuration est taillée sur mesure pour la Ender 3 V3 SE et ses spécificités. C'est la plus récente de l'atelier, rapide et performante.

Composant	Spécification
🖥️ Carte Mère	[Carte mère 32-bit Creality d'origine]
🔩 Extrudeur	[Extrudeur Direct Drive d'origine]
✨ Sonde Z	[CR-Touch intégré]
होस्ट Klipper Host   [Raspberry Pi 4 - 4Go]

🔧 Ender 3 V2
(Pensez à ajouter une belle photo de votre imprimante et à mettre le lien ici !)

Configuration pour ma fidèle Ender 3 V2, modifiée et améliorée au fil du temps. Une machine fiable qui a fait ses preuves.

Composant	Spécification
🖥️ Carte Mère	Carte mère 32-bit Creality d'origine]
🔩 Extrudeur	[Extrudeur BMG Clone]
✨ Sonde Z	[BL-Touch]
होस्ट Klipper Host	[Raspberry Pi 4 - 4Go]
➕ Autres	[Double axe Z, Plateau PEI, Capteur fin de fillaments]

📂 Structure du Dépôt
Ce projet est organisé de manière simple, avec une séparation claire entre chaque machine :

/Ender3_V3_SE : Contient l'intégralité de la configuration pour la Ender 3 V3 SE.
/Ender3_V2 : Contient l'intégralité de la configuration pour la Ender 3 V2.

📦 Logiciels et Modules Clés
Ce setup repose sur les excellents logiciels open-source suivants :

🔹 Klipper : Le firmware qui décuple la puissance de l'imprimante.
🔹 Moonraker : L'API qui fait le pont entre Klipper et l'interface utilisateur.
🔹 Mainsail : Mon interface web de choix pour piloter les imprimantes.
🔹 KAMP : Pour un nivellement du plateau et une purge intelligents et adaptatifs.
🔹 KIAUH : Pour l'installation de l'environnement sur MainsailOS.
