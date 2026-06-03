# Chess.Card

**chess.card** est une petite application web récréative qui génère des cartes "joueur" à collectionner basées sur les statistiques réelles des profils **chess.com**. 

Tape un pseudo, l'outil récupère les données via l'API publique de chess.com, analyse le style de jeu (ouvertures, zeitnot, taux de mat, etc.) et fond une carte unique dont le design et les couleurs évoluent en fonction du classement (Elo).

🌐 **Démo en ligne :** [lusowall.github.io/chesscard](https://lusowall.github.io/chesscard)

---

## Fonctionnalités

* **Génération de carte Solo :** Calcule un score global (OVR), des statistiques de RPG (Tactique, Attaque, Défense...) et un "Archétype" de joueur (ex: *Le Boucher*, *Le Pacifiste*, *Le Noctambule*).
* **Mode Comparaison (Versus) :** Mets deux joueurs face à face pour comparer leurs cartes et leurs statistiques détaillées.
* **Analyse de données (Flex & Fun) :** Heatmap des heures de jeu, pires némésis, ouvertures fétiches, et taux de coups joués en "zeitnot".
* **Export Facile :** Télécharge la carte en PNG, génère une bannière complète, copie l'image directement dans le presse-papier, ou génère un lien de partage direct.
* **100% Client-side :** Tout tourne dans le navigateur. Les appels réseau sont faits directement vers l'API publique de chess.com.

> **Avertissement :** Cet outil est 100% récréatif. Les notes générées sont des approximations pour le fun et le flex, pas une analyse sérieuse d'un moteur d'échecs.

## Installation & Lancement

Le projet est un simple fichier statique (`index.html`). Aucun build, aucun framework complexe n'est requis.

## Technologies utilisées
HTML5 / CSS3 (Variables CSS, Grid, animations 3D pour le retournement de carte).

JavaScript (Vanilla).

html2canvas : Pour la capture et l'export des cartes en images PNG.

API Publique Chess.com.
