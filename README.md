# ProjetInfoMus

***
## Description du projet

"Séquenceur" de huit boucles synchronisées sur la première contrôlables en MIDI via l'application TouchOSC (iPad).<br>
Pour jouer sur ce séquenceur, on a le choix entre deux instruments (basés sur des patchs que j'ai récupérés sur internet) :
- Granulizer, qui fait de la synthèse granulaire à partir de ce qu'il reçoit comme signal audio (via un micro).
- Wavetable, contrôlables par un clavier MIDI, qui permet de jouer des notes avec différentes formes d'ondes.

Tout le reste du patch, ainsi que le layout iPad, ont été faits par mes soins.

![Image text](/screenshots/iPadUIScreenshot.png)
Layout TouchOSC (iPad)

![Image text](/screenshots/main.png)
Interface principale "clean" du patch

![Image text](/screenshots/seq.png)
"Vrai" interface principale du patch

![Image text](/screenshots/gran.png)
Granulizer

![Image text](/screenshots/wave.png)
Wavetable

![Image text](/screenshots/loop.png)
Looper 1

***
## Issues

J'ai eu des soucis techniques avec mon ordinateur, donc je n'ai pas pu faire de vidéo pour le moment.<br>
De plus, bien que le Granulizer fonctionnait parfaitement seul, il ne fonctionne pas dans le patch sur mon ordinateur, à mon avis à cause d'une surcharge du CPU.<br>
Je n'ai malheureusement pas pu tester le patch sur un autre ordinateur pour voir si le soucis venait du mien (qui commence à se faire vieux).<br>
Il y a d'ailleurs probablement des moyens d'optimiser le patch, mais je n'ai pas eu le temps de me pencher là-dessus.<br>
Je n'ai pas réussi à connecter mon iPad en OSC, j'ai donc du le connecter en MIDI et de ce fait je n'ai pas pu contrôler de paramètres avec l'accéléromètre de l'iPad.<br>
J'ai aussi eu des soucis avec l'installation de librairies externes, j'ai donc décidé de tout faire en vanilla. 
