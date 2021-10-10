# Exercice : Mon meuble SOLID, Le KALAX

## Pr�sentation
Le but de cet exercice est de mettre en pratique les principes SOLID, IOD, KISS et Fonctionnel
vs technique.

## Exercice 1 : Le squelette des abstractions
Cr�er un projet Java (Maven).
Cr�er une interface meuble avec les specifications suivantes :
* un meuble a une hauteur
* un meuble a une largeur
* un meuble a une �paisseur

Cr�er une interface meuble kalax avec les specifications suivantes :
* un kalax est un meuble
* un kalax a un certain nombre d'emplacements
* il est possible de mettre un composant d'emplacement Kalax dans un emplacement
* il est possible de retirer un composant d'emplacement Kalax dans un emplacement

Cr�er une interface emplacement de meuble avec les specifications suivantes :
* un emplacement de meuble peut ranger des objets
* un emplacement de meuble permet de retirer des objets
* un emplacement de meuble permet de lister des objets

Cr�er une interface composant d'emplacement kalax avec les specifications suivantes :
* un composant d'emplacement kalax est un emplacement de meuble
* un composant d'emplacement kalax peut �tre tir� pour voir son contenue

Cr�er une interface tiroir avec les specifications suivantes :
* un tiroir peut �tre ouvert

Cr�er une interface composant avec les specifications suivantes :
* un composant poss�de une couleur

Cr�er une interface composant en tissu avec les specifications suivantes :
* un composant en tissu est un composant
* un composant en tissu peut �tre lav� a l'eau

Cr�er une interface composant en bois avec les specifications suivantes :
* un composant en bois est un composant
* un composant en bois peut �tre repaint avec une certaine couleur

Cr�er une interface objet qui peut �tre rang� avec les specifications suivantes :
* un objet qui peut �tre ranger poss�de un nom

Cr�er une interface composant s�curiser avec les specifications suivantes :
* c'est un composant 
* il faut une cl� pour le d�verrouiller

Utiliser des termes correspondant aux besoins list� ci-dessus.

Vous venez de faire de la s�gr�gation d'interface en respectant le principe de responsabilit�
unique.

### Exercice 2 : Implementation de Kalax
Cr�er une classe meuble kalax 4x2 :
* c'est une meuble kalax
* il poss�de 4 emplacements
* il fait 35 cm de profondeur
* il fait 80 cm de large
* il fait 140 cm d�haut

Impl�ment� les m�thodes necessaries.

Cr�er un autre meuble kalax 4x4 en ajustant les valeurs du meuble kalax 4x2
```
Bonus :
Cr�er une classe abstraite permettant de simplifier la cr�ation de meuble kalax en g�n�ralisant
certaines m�thodes.
```

### Exercice 3 : Impl�mentation des composants

Cr�er une classe tiroir pour emplacement kalax :
* c'est un composant d'emplacement kalax
* c'est un tiroir
* c'est un composant en bois

Cr�er une classe boite pour kalax :
* c'est un composant d'emplacement kalax
* c'est un composant en bois

Cr�er une classe coffre-fort pour kalax :
* c'est un composant d'emplacement kalax
* c'est un composant s�curis�

Cr�er une classe boite en tissu :
* c'est un composant d'emplacement kalax
* c'est un composant en tissu

Impl�ment� les diff�rentes m�thodes. 

Vous venez de faire un code respectant les principes SOLID et IOD.

### Exercice 4 : Assemblage
Comme avec le meuble. �crire un code qui assemble des meubles kalax et des composants d'emplacement
kalax.