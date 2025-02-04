# Technologies

Le projet repose sur l’intégration de plusieurs technologies matérielles et logicielles pour créer une expérience immersive où les dessins réalisés sur un tableau blanc interagissent avec des éléments sonores et visuels en temps réel.

## Matériel

### Interface interactive

Les interfaces et capteurs sont utilisés pour capter l'interaction des utilisateurs et générer des réponses en fonction de leur dessin.

- **Tableau blanc** : Le tableau sert de surface de dessin, et les utilisateurs interagissent directement avec lui en traçant des lignes et formes.
- **Marqueurs** : Les utilisateurs dessinent sur le tableau avec des marqueurs qui seront suivis par la caméra.

### Caméra

La caméra est placée au-dessus du tableau blanc pour filmer en temps réel les dessins effectués par les utilisateurs et les retranscrire dans l'environnement interactif.

- **Sony a6500** : Placée au-dessus du tableau, cette caméra haute définition capte les dessins en temps réel. Elle permet une prise de vue précise et fluide des dessins, assurant ainsi la synchronisation avec les éléments sonores et visuels générés par le système.

### Processeurs et Ordinateurs

Les processeurs traitent les données collectées par la caméra pour générer des interactions dynamiques en temps réel, en intégrant les éléments visuels et sonores de manière cohérente.

- **PC** : Utilisé pour traiter les vidéos capturées par la caméra, ainsi que pour gérer les rendus visuels et la diffusion sonore à partir de TouchDesigner.

### Diffusion et affichage

L'affichage visuel et la diffusion sonore sont essentiels pour renforcer l’immersion de l’expérience interactive.

- **Projecteurs haute résolution** : Diffusent les dessins et les éléments visuels générés en temps réel sur un mur ou une autre surface, en fonction des actions de l'utilisateur.
- **Écouteurs** : Diffusent des ambiances sonores préalablement créées, qui évoluent en fonction des dessins et interactions de l'utilisateur.

## Logiciel

### Logiciels de création multimédia

Les logiciels de création multimédia sont utilisés pour lier les dessins sur le tableau blanc aux effets visuels et sonores qui en résultent.

- **TouchDesigner** : Utilisé pour la gestion des projections vidéo en temps réel et pour générer des effets visuels qui réagissent directement aux dessins des utilisateurs. Il assure aussi la diffusion des ambiances sonores associées aux formes et couleurs détectées.

### Algorithmes de détection

Ces algorithmes permettent de détecter les dessins en temps réel et de générer des événements en fonction des formes et couleurs dessinées sur le tableau blanc.

- **Détection de forme et de couleur** : TouchDesigner analyse les images captées par la caméra pour reconnaître les formes et couleurs utilisées. Ces informations sont ensuite traduites en effets visuels et déclenchements sonores.

### Médias génératifs

TouchDesigner permet de générer du contenu visuel en temps réel, créant une expérience interactive et immersive unique pour chaque utilisateur.

- **Vidéo interactive** : Les dessins sont projetés sous forme de compositions visuelles dynamiques, et l’environnement réagit en fonction de l’évolution du dessin.
- **Ambiances sonores préenregistrées** : Plutôt que d’être générés en temps réel, les sons sont sélectionnés et déclenchés selon les dessins détectés par TouchDesigner, assurant une cohérence entre l’image et l’audio.

## Récapitulatif

L’intégration des technologies matérielles et logicielles permet de créer une expérience immersive et interactive où les dessins réalisés par les utilisateurs sur un tableau blanc prennent vie à travers des projections visuelles et des effets sonores en temps réel. La caméra Sony a6500 joue un rôle clé dans la capture précise des dessins, tandis que **TouchDesigner** synchronise les effets visuels et déclenche les ambiances sonores, créant une expérience unique pour chaque utilisateur.
