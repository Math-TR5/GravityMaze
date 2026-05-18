# GravityMaze

## Projet - Communication Sans Fil
MANUKIEVITCH Krystal, TROUVÉ Mathilde et PEROLINI Poe-iti

*Ce projet est réalisé dans le cadre du module Communication Sans Fil en Licence 1 à l’Université
Nice Sophia Antipolis*

### 📘 Présentation du projet
*GravityMaze* est un jeu dont l'objectif est de faire parcourir un labyrinthe à une bille en inclinant le plateau du labyrinthe à distance. 

### 🧭 Motivation  
Étudiantes en licence **Sciences et Technologies – Parcours Préparatoire au Professorat des Écoles (PPPE)**, nous avons voulu créer un jeu interactif, nous permettant ainsi d’explorer la communication sans fil tout en rendant l’apprentissage plus accessible, ludique et engageant.
 
### 🎯 Objectif du projet
Afin de donner une direction claire à notre démarche, nous avons défini les objectifs suivants, structurant le développement et l’évaluation de notre jeu interactif : 
- Contrôler un labyrinthe à distance
- Utiliser un accéléromètre comme manette
- Transmettre les données via LoRaWAN
- Faire bouger la plateforme avec des servomoteurs

### ❓ Problématique
*Comment contrôler un système mécanique à distance de manière fiable et sans fil ?*


###  🔧 Matériel et fonctions
Pour créer ce jeu, nous avons réalisé plutieurs et utilisé du matériel prêté par l'**Université Nice Côte d'Azur**.

### ⚙️ Structure
Voici la liste des pièces que nous avons réalisé pour la structure de notre jeu *(cf. **Illustration_structure_du_jeu.pdf**)*

**1. Le socle :** il est constituée d'une seule pièce, que nous avons réalisé en utilisant la méthode de la découpe laser. Il permet de tenir et surélever le pied et le plateau, tout en camouflant les composants électroniques.


**2. Le pieds articulé :** il est composé de trois pièces que nous avons modélisé, grâce au logiciel *Fusion360*, et imprimé en 3D. Elles permettent de combiner les mouvements des deux servomoteurs. 


**3. Le plateau :** il est constituée d'un seule pièce. Nous avons utlisé le logiciel *Fusion360* afin de modéliser en 3D cette pièce, que nous avons par la suite imprimé en 3D.


**4. La télécommande :** cette quatrième pièce de la structure du jeu est constituée de deux pièces. Nous avons modélisé et imprimé en 3D les parois et utilisé la découpe laser pour le fond et le couvercle coulissant. La télécommande permet d'abriter l'accéléromètre qui va contrôler l'inclinaison du labyrinthe à distance : elle n'est donc pas reliée aux autres pièces de la structure du jeu.


### 🔌 Composants électroniques
Voici la liste des composants électroniques, prêtés par l'**Université Nice Côte d'Azur**, qui ont été nécessaires à la réalisation de ce projet.

**1. Deux servomoteurs**: situés dans le pied du labyrinthe, ils permettent d'incliner le plateau et ainsi faire bouger la bille. L'un permet de contrôler l'inclinaison selon l'axe Ox et l'autre selon l'axe Oy *(cf. **contrôle_des_axes_servomoteurs.pdf**)*.


**2- Un accéléromètre**: composant principal de la télécommande, il va permettre de contrôler le labyrinthe à distance en receuillant des données concernant l'inclinaison des deux axes définis précédemment.


**3- Deux cartes UCA**: 

- la première est située dans la télécommande et contient l'accéléromètre. Elle sert d'émetteur afin de transmettre les informations récupérées par l'accéléromètre.
- la deuxième est située dans le socle. Elle sert de récepteur afin de traduire, pour les servomoteurs, les données reçus concernant l'inclinaison des deux axes 


**4- Fils** : ils permettent de lier les différents composants électroniques *(cf. **Schéma_de_montage.pdf**)*

**5- Deux batteries** : elles permettent d'alimenter les deux cartes UCA (celle de la télécommande et celle dans le socle).

### 🖥️ Programmation

*(à compléter!!!!!!!)*

## 🗓️ Planning
La réalisation des différentes tâches constituant notre projet est résumée dans le fichier **diagramme_de_Gantt.pdf**.


## 📚 Conclusion
Ce projet nous a permis d’explorer de manière concrète et progressive les principes fondamentaux de la communication sans fil, en les traduisant sous la forme d’un jeu interactif pensé pour des apprenants débutants. La conception de ce dispositif ludique nous a amenées à comprendre les mécanismes essentiels d’une transmission radio tout en réfléchissant à la manière de les rendre accessibles, visuels et motivants. Au‑delà de l’aspect technique, ce travail nous a également offert l’occasion de mobiliser une démarche pédagogique cohérente avec notre formation PPPE (Parcours Préparatoire au Professorat des Écoles), en cherchant à allier rigueur scientifique et approche didactique. Le résultat final constitue ainsi une première proposition de médiation scientifique, capable de faciliter l’appropriation de notions complexes grâce à une expérience d’apprentissage engageante et intuitive.
