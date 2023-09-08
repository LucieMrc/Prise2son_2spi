# Prise2son_2spi

*[english version](https://github.com/LucieMrc/SoundRecording_sp33d)*

**Ou comment faire une prise de son en autonomie pour les voix-off, les podcasts et ainsi de suite.**

Pré-requis : être dans le studio son et avoir quelqu'un qui parle dans la pièce en face. 

## 1. Branchements

La carte son doit être branchée à l'ordi :

![Carte son](./images/img1.jpg)

Elle doit être allumée :

![Carte son](./images/img2.jpg)

Et il doit y avoir des trucs branchés dessus : 

![Carte son](./images/img3.jpg)

Pour régler le gain du micro (avoir un volume adéquat si la personne va crier dans le micro ou au contraire murmurer par exemple), c'est le second potard à gauche sur la face de la carte son :

![carte son](./images/entree_focusrite.png)

<details><summary> La différence entre gain et volume</summary>
Le gain c'est l'amplitude du signal d'entrée (à quel point le micro capte le son), tandis que le volume c'est l'amplitude du signal de sortie (à quel point les enceintes font du bruit).
</details>

On peux ainsi augmenter ou diminuer le gain du micro régie (celui qui permet de communiquer avec la personne dans la cabine) ou du micro cabine (celui qu'on enregistre), le volume des enceintes de monitoring dans la régie, ainsi que le volume du casque de la cabine, et de la seconde sortie si on utilise un casque dans la régie par exemple.

Attention, il faut baisser le volume des enceintes si on utilise le micro régie pour éviter les effets larsen.

Il faut également allumer les enceintes grâce au bouton derrière :
![Enceintes](./images/img4.jpg)

## 2. Enregistrer avec Reaper

Ouvrir Reaper.

// photo

Cliquer sur "Still Evaluating".

Créer un track avec `Track` > `Insert new track`.

![nouveau track](./images/screen1.png)

Pour pouvoir enregistrer sur le track, cliquer sur le bouton record ⏺️ sur le track soit en haut à gauche dans la liste des tracks, soit en bas à gauche dans le panneau de mix.

![nouveau track](./images/screen2.png)
![nouveau track](./images/screen3.png)

On voit alors le niveau de son du micro dans les vu-mètres.

Il suffit alors de cliquer sur le bouton record ⏺️ principal pour enregistrer le son du micro sur le track.

![nouveau track](./images/screen4.png)

Pour recouper l'enregistrements, on peux soit sélectionner la partie du son à conserver et faire clic-droit > `Crop project to selection`, ou alors sélectionner les parties du son à enlever et faire clic-droit > `Remove contents of selection`.

![nouveau track](./images/screen5.png)

Pour exporter le son, faire `File` > `Consolidate/Export tracks...` .

![nouveau track](./images/screen6.png)

Gérer les réglages de l'export :

![nouveau track](./images/screen7.png)

Choisir notamment le format de fichier avec `Consolidate to` (WAV, AIFF, MP3), et l'emplacement de l'export avec `Output consolidated files to directory:`.

## 3. Enregistrer avec FL Studio

### Réglages FL Studio

Ouvrir FL Studio.

Ouvrir les `Audio Settings` dans la liste `Options`.

![Carte son](./images/capture2.png)

Dans la liste `Device`, sélectionner notre carte son `Focusrite USB ASIO`.

![Carte son](./images/capture3.png)

*Attention à bien prendre la Focusrite dans la partie `Asio Device` de la liste.*

Voilà l'interface quand tout est bien connecté :

![Carte son](./images/capture4.png)

### Enregistrement

Cliquer sur l'icône micro 🎙️ en haut à droite.

![Carte son](./images/capture1.png)

Choisir `Into Edison audio editor/recorder`.

![Carte son](./images/capture5.png)

Cliquer sur le bouton enregistrer ⏺️ pour commencer l'enregistrement.

![Carte son](./images/capture6.png)

Le bouton enregistrer ⏺️ devient rouge, et on peux cliquer sur le bouton stop ⏹️ pour arrêter.

![Carte son](./images/capture7.png)

Pour sauvegarder l'enregistrement, cliquer sur le bouton disquette 💾 et choisir `Save sample as`.

![Carte son](./images/capture9.png)

Pour créer un nouvel enregistrement, cliquer sur le bouton disquette 💾 et choisir `New`.

![Carte son](./images/capture8.png)