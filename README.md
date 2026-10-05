# CubeU v0.0.3

Prototype d'un emulateur GameCube natif pour Wii U sous Aroma.

## Nouveautes

- interface centree sur une bibliotheque de jeux ;
- recherche recursive des fichiers `.iso` et `.gcm` dans `SD:/games/` ;
- lecture du titre GameCube directement dans l'en-tete du disque ;
- affichage du Game ID, de la region et de la taille ;
- fiche individuelle pour chaque jeu ;
- menu Parametres et page A propos ;
- informations techniques masquees dans une page separee ;
- test CPU interne toujours disponible depuis A propos.

## Organisation des jeux

```text
SD:/games/Super Mario Sunshine/game.iso
SD:/games/Mario Kart Double Dash/game.gcm
SD:/games/Luigis Mansion.iso
```

CubeU parcourt les sous-dossiers jusqu'a quatre niveaux et indexe jusqu'a 200 jeux.

## Commandes

- Haut/Bas : naviguer
- A : valider ou ouvrir la fiche
- B : revenir
- X : actualiser la bibliotheque
- Y : test moteur depuis A propos
- + : quitter

## Limites

La v0.0.3 ne lance pas encore les jeux. Le bouton Lancer indique clairement que le moteur GPU, le DSP audio, le lecteur de disque emule et les autres composants ne sont pas encore implementes.


Ce projet n'aura plus jamais de mise a jour du aux faite que UwUVCI AIO existe
