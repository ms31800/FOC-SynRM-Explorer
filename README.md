# FOC-SynRM-Explorer

Explorateur interactif du contrôle vectoriel (FOC) appliqué à une machine SynRM/MCC.  
L’objectif est d’offrir un outil pédagogique complet permettant de visualiser :

- La chaîne de contrôle FOC (boucle de vitesse, régulateurs Id / Iq)
- Les transformations Clarke et Park
- L’évolution du repère d, q
- Le fonctionnement de l’onduleur triphasé
- Les courants dans les enroulements (animation temps réel)
- Les flux, couples, angles et grandeurs électriques
- Un schéma bloc FOC interactif avec tooltips et panneaux d’explications

➡ **Tester l’application en ligne :**  
https://ms31800.github.io/FOC-SynRM-Explorer/


##  Fonctionnalités principales

###  Animation temps réel
Visualisation dynamique d’un moteur SynRM / MCC sous contrôle vectoriel.

###  Schéma FOC interactif
Au survol et au clic :
- Tooltips explicatifs
- Panneau de description détaillée pour chaque bloc (PI, Park, Clarke, estimations…)

Le schéma SVG est chargé dynamiquement via `fetch()` pour garder le code HTML propre 

###  Architecture pédagogique
L’interface a été conçue pour faciliter la compréhension :
- Paramètres ajustables
- Valeurs affichées en temps réel
- Repères électriques et mécaniques
- Séparation claire entre bloc commande et bloc puissance



##  Technologies utilisées

- **HTML5 / CSS3**
- **JavaScript**
- **SVG dynamique**
- **fetch() / DOMParser**
- **p5.js** pour l’animation 
- **GitHub Pages** pour l’hébergement



## Origine du projet

Il fait suite à la création d'une FCIL (Formation Complémentaire d’Initiative Locale):
Conseils,Installations, Maintenance Des motorisations électriques industrielles à haute efficacité énergétique qui est dispensée dans notre établissement, et qui aborde le dimensionnement 
ainsi que la mise en oeuvre de ces nouvelles générations de moto variateurs. 

##  Déploiement

L’application est hébergée gratuitement via **GitHub Pages**.  
Toute mise à jour du dépôt met automatiquement à jour la version en ligne.


##  Licence

Le projet est en accès libre, consultable et réutilisable, citez juste l'établissement qui en est l'auteur lors de vos séances: LPO Paul MATHOU - 31210 GOURDAN-POLIGNAN



##  Remerciements

Projet conçu pour mieux illustrer le pilotage FOC d’une machine SynRM.  
Merci aux personnes ayant contribué aux tests, aux idées pédagogiques et aux retours techniques.
