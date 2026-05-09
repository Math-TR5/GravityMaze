# GravityMaze

## Projet - Communication Sans Fil
MANUKIEVITCH Krystal, TROUVE Mathilde et PEROLINI Poe-iti

*Université Nice Côté d'Azur*


## 📘 Présentation du projet
*GravaityMaze* est un jeu dont l'objectif est de faire parcourir un labyrinthe à une bille en inclinant le plateau du labyrinthe à distance. 

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


##  🔧 Matériel et fonctions
Pour créer ce jeu, nous avons utilisé du matériel prêté par l'**Université Nice Côte d'Azur**, mais également réalisé plusieurs pièces.

### ⚙️ Structure
La structure de notre jeu se divise en **quatre parties** *(numérotées sur le schéma ci-contre)* :

**1. Le socle :**
Cette première partie de la structure du jeu est constituée d'une seule pièce, que nous avons réalisé en carton et recouvert de papier. Elle permet de tenir le pied et le labyrinthe, tout en camouflant les composants électroniques.

*(photo du socle terminé)*

**2. Le pieds articulé :**
Cette deuxième partie de la structure du jeu est composé de trois pièces que nous avons modélisé et imprimé en 3D. Elles permettent de combiner les mouvements des deux servomoteurs. 

*(photos modélisations des pièces et du pied complet)*

**3. Le Labyrinthe :**
Cette troisième partie de la structure du jeu est constituée d'un seule pièce. Nous avons utlisé le logiciel *Fusion360* afin de modéliser en 3D cette pièce, que nous avons par la suite imprimé en 3D.

*(photo des modélisation + de la pièce imprimée)*

**4. La télécommande :**
Cette quatrième et dernière pièce de la structure du jeu est constituée d'une seule pièce en carton, recouverte d'un papier. Cette pièce abrite l'accéléromètre qui va permettre de contôler l'inclinaison du labyrinthe à distance : elle n'est donc pas reliée aux autres pièces de la structure du jeu.

*(schéma et photo)*

### 🔌 Composants électroniques
Voici la liste des composants électroniques qui ont été nécessaires à la réalisation de ce projet:

**1. Deux servomoteurs :**
Situés dans le pied du labyrinthe, ils permettent d'incliner le plateau et ainsi faire bouger la bille. L'un permet de contrôler l'inclinaison selon l'axe Ox *(cf. **Figure 1.a**)* et l'autre selon l'axe Oy *(cf. **Figure 1.b**)*

*(schémas de contrôle des inclinaisons des servomoteurs + photo)*

**2- Un accéléromètre**



**3- Une carte UCA**


**4- Des fils**
Ils permettent de lier les différents composants électroniques selon le schéma de montage suivant :

*(schéma de montage)*


### 🖥️ Programmation


## 🗓️ Planning
La réalisation des différentes tâches constituant notre projet est résumée dans le dirgamme de Gantt ci-dessous :

*(digramme de Gantt)*

## 📁 Annexes
- premier croquis du projet
- premier prototype
- 

## 📚 Conclusion
Ce projet nous a permis d’explorer de manière concrète et progressive les principes fondamentaux de la communication sans fil, en les traduisant sous la forme d’un jeu interactif pensé pour des apprenants débutants. La conception de ce dispositif ludique nous a amenées à comprendre les mécanismes essentiels d’une transmission radio tout en réfléchissant à la manière de les rendre accessibles, visuels et motivants. Au‑delà de l’aspect technique, ce travail nous a également offert l’occasion de mobiliser une démarche pédagogique cohérente avec notre formation PPPE (Parcours Préparatoire au Professorat des Écoles), en cherchant à allier rigueur scientifique et approche didactique. Le résultat final constitue ainsi une première proposition de médiation scientifique, capable de faciliter l’appropriation de notions complexes grâce à une expérience d’apprentissage engageante et intuitive.
