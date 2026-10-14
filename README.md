<div align="center">

# Visiion

**Ta bibliothèque de films et séries, façon site de streaming.**

[**Télécharger la dernière version**](https://github.com/6j9f89rrvj-stack/Visiion_App/releases/latest)

</div>

Ce dépôt contient **Visiion** pour Windows 10 / 11 : l'installateur
`Visiion_x.y.z_x64-setup.exe` (recommandé) et la version portable `Visiion.exe`.

Visiion parcourt tes dossiers de vidéos et les présente comme Apple TV : affiches, résumés, distribution et
bandes-annonces (TMDB), qualité et pistes audio (ffprobe), lecture dans ton lecteur (VLC, mpv, PotPlayer, MPC…)
avec reprise et « vu » automatiques, « Où regarder », Ma liste et Ma collection.

## Installation

1. Télécharge `Visiion_x.y.z_x64-setup.exe` depuis la [dernière version](https://github.com/6j9f89rrvj-stack/Visiion_App/releases/latest).
2. Windows peut afficher « Windows a protégé votre ordinateur » (l'application n'est pas signée par un
   certificat payant) : **Informations complémentaires** › **Exécuter quand même**.
3. Visiion s'installe pour ton compte, sans droits administrateur, avec un raccourci dans le menu Démarrer.

Il te faudra une clé TMDB gratuite pour les affiches et résumés, et FFmpeg pour lire la qualité des fichiers
(`winget install Gyan.FFmpeg`) ; tout est expliqué dans l'app (*Réglages › Avancé* et l'aide, `F1`).

Ce produit utilise l'API TMDB mais n'est ni approuvé ni certifié par TMDB.
