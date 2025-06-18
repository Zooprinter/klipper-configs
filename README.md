# 🤖 Configurations Klipper de Zooprinter

[![Klipper](https://img.shields.io/badge/Klipper-Firmware-blueviolet)](https://www.klipper3d.org/) [![Mainsail](https://img.shields.io/badge/UI-Mainsail-red)](https://docs.mainsail.xyz/)

Bienvenue ! 👋 Ce dépôt contient mes configurations Klipper personnelles, optimisées pour mes imprimantes 3D. Chaque imprimante fonctionne sur son propre serveur Klipper, ce qui explique pourquoi chaque dossier est entièrement autonome.

## 🖨️ Mes Imprimantes

---

### 🔥 Ender 3 V3 SE

Cette configuration est taillée sur mesure pour la Ender 3 V3 SE et ses spécificités. C'est la plus récente de l'atelier, rapide et performante.

| Composant | Spécification |
| :--- | :--- |
| 🖥️ **Carte Mère** | Carte mère 32-bit Creality d'origine |
| 🔩 **Extrudeur** | Extrudeur Direct Drive d'origine |
| ✨ **Sonde Z** | CR-Touch intégré |
| 🤖 **Klipper Host** | Raspberry Pi 4 - 4Go |

➡️ **[Voir la configuration complète pour la Ender 3 V3 SE](./Ender3_V3_SE/)**

---

### 🔧 Ender 3 V2

Configuration pour ma fidèle Ender 3 V2, modifiée et améliorée au fil du temps. Une machine fiable qui a fait ses preuves.

| Composant | Spécification |
| :--- | :--- |
| 🖥️ **Carte Mère** | Carte mère 32-bit Creality d'origine |
| 🔩 **Extrudeur** | Extrudeur BMG Clone |
| ✨ **Sonde Z** | BL-Touch |
| 🤖 **Klipper Host** | Raspberry Pi 4 - 4Go |
| ➕ **Autres** | Double axe Z, Plateau PEI, Capteur fin de filaments |

➡️ **[Voir la configuration complète pour la Ender 3 V2](./Ender3_V2/)**

---

## 📂 Structure du Dépôt

Ce projet est organisé de manière simple, avec une séparation claire entre chaque machine. Chaque dossier est 100% autonome.

-   `./Ender3_V3_SE` : Contient l'intégralité de la configuration pour la Ender 3 V3 SE.
-   `./Ender3_V2` : Contient l'intégralité de la configuration pour la Ender 3 V2.

## 📦 Logiciels et Modules Clés

Ce setup repose sur les excellents logiciels open-source suivants :

-   🔹 **[Klipper](https://www.klipper3d.org/)** : Le firmware qui décuple la puissance de l'imprimante.
-   🔹 **[Moonraker](https://moonraker.readthedocs.io/)** : L'API qui fait le pont entre Klipper et l'interface utilisateur.
-   🔹 **[Mainsail](https://docs.mainsail.xyz/)** : Mon interface web de choix pour piloter les imprimantes.
-   🔹 **[KAMP](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)** : Pour un nivellement du plateau et une purge intelligents et adaptatifs.
-   🔹 **[KIAUH](https://github.com/th33xitus/kiauh)** : Pour l'installation et la maintenance de l'environnement Klipper.
