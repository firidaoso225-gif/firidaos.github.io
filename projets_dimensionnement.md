# Projets de dimensionnement - BUT 3 Génie Chimique - Génie des Procédés

## Introduction
Dans le cadre de ma troisième année de BUT Génie Chimique - Génie des Procédés, j’ai réalisé deux projets de dimensionnement industriel :  
- **S5 : Dimensionnement thermique d’un réacteur à double enveloppe**  
- **S6 : Dimensionnement d’une colonne d’absorption à garnissage**

Ces projets m’ont permis d’appliquer les méthodes de calcul utilisées en ingénierie des procédés : bilans thermiques, bilans matière, transferts de chaleur, transferts de matière, hydrodynamique, corrélations industrielles, optimisation énergétique et choix de matériel.


# Projet S5 - Dimensionnement thermique d’un réacteur

## Objectif
Dimensionner le système de chauffage d’un réacteur à double enveloppe afin d’atteindre une température de réaction en **moins de 20 minutes**, tout en respectant les contraintes industrielles.

> « L’objectif de cette étude est d’évaluer la faisabilité du chauffage du milieu réactionnel dans les conditions nominales de fonctionnement. »  

## 1. Analyse du réacteur
- Réacteur fermé à fond plat  
- Double enveloppe pour chauffage  
- Agitateur Mixel T4P (4 pales, 45°)  
- Pompe pour circulation du fluide caloporteur  
- Hypothèse : pertes thermiques négligées


## 2. Bilan thermique
Calcul basé sur la :

- Détermination de la surface d’échange  
- Détermination du coefficient global de transfert thermique **U**  
- Intégration de l’équation pour obtenir le temps de chauffe

### Résultat en conditions nominales
- **Temps de chauffe = 44,28 min**  
→ Non conforme au cahier des charges (20 min max)


## 3. Optimisation

### a) Augmentation de la vitesse d’agitation
- Calcul du nombre de puissance Np  
- Détermination de la vitesse maximale admissible : **Nmax = 21,26 rps**  
- Recalcul de hr, U et tch

→ **Temps de chauffe optimisé : 19,28 min**  
→ Conforme au cahier des charges

### b) Augmentation du débit du fluide caloporteur
- Calcul des pertes de charge (canalisation + double enveloppe)  
- Puissance hydraulique disponible : 4000 W  
- Débit maximal : **0,0253 m³/s**

→ Temps de chauffe ≈ **42 min**  
→ Insuffisant seul

### c) Optimisation conjointe (agitation + débit)
Plusieurs couples (N, Q) permettent d’atteindre **tch = 20 min**.


## Synthèse du projet réacteur
Ce projet m’a permis de :
- maîtriser les bilans thermiques  
- utiliser les corrélations de convection (Re, Pr, Nu)  
- optimiser un procédé industriel  
- comprendre l’impact de l’agitation et du débit sur les transferts thermiques  
- proposer des solutions réalistes pour atteindre un objectif industriel


# Projet S6 - Dimensionnement d’une colonne d’absorption à garnissage

## Objectif
Dimensionner une colonne d’absorption pour éliminer **95 % du SO₂** d’un gaz industriel contenant **8,5 % vol. SO₂**, avec un débit de **4500 ± 500 kg/h**.

> « L’objectif est de dimensionner une colonne d’absorption capable d’atteindre ce rendement tout en respectant les contraintes de fonctionnement imposées. »  

## 1. Bilans matière
- Débit SO₂ entrant : **766 kg/h**  
- SO₂ absorbé : **95 % → 727 kg/h**  
- SO₂ résiduel dans le gaz : **38,28 kg/h**  
- Débit air sec : **3734 kg/h**

Détermination du débit liquide minimal via la courbe d’équilibre :

→ **Lmin = 7,71 × 10⁴ kg/h**  
→ Débit choisi : **L2 = 1,0 × 10⁵ kg/h**

## 2. Choix du garnissage
- Selles Intalox (performances supérieures aux selles de Berl)  
- Diamètre caractéristique : **7,62 × 10⁻² m**  
- Respect du critère industriel :  


## 3. Dimensionnement du diamètre (diagramme d’Eckert)
- Calcul du paramètre X  
- Choix d’une perte de charge optimale : **29 mmH₂O/m**  
- Détermination de Y par interpolation logarithmique  
- Calcul du flux massique gazeux G’

### Résultat
- Diamètre théorique : **0,96 m**  
- Diamètre industriel retenu : **0,89 m (36 inches)**  
- Vérification hydrodynamique : pas d’engorgement (flooding)


## 4. Hauteur du garnissage
Calcul basé sur la :

- Détermination de NUT (méthode des trapèzes)  
- Détermination de HUT (méthode d’Onda)  
- Vérification du critère industriel : Z/D avce Z=NUT*HUT et D = diamètre de la colonne 


## Synthèse du projet colonne
Ce projet m’a permis de :
- réaliser un dimensionnement complet d’une colonne d’absorption  
- utiliser le diagramme d’Eckert  
- appliquer les méthodes NUT/HUT  
- choisir un garnissage adapté  
- vérifier les critères hydrodynamiques et industriels  
- maîtriser les bilans matière et les transferts de matière


# Conclusion générale
Ces deux projets de dimensionnement m’ont permis d’acquérir une vision concrète des méthodes utilisées en ingénierie des procédés.  
Ils illustrent ma capacité à :

- analyser un procédé industriel  
- réaliser des bilans thermiques et matière  
- utiliser des corrélations industrielles  
- optimiser des paramètres opératoires  
- proposer des solutions réalistes et conformes aux contraintes industrielles

Ils constituent une base solide pour mon futur rôle d’ingénieure procédés.
