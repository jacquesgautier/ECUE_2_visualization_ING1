# Cartes thématiques avec MAGRIT et Kepler.gl

## Présentation de MAGRIT

## Représenter des donnnées quantitatives dans une carte

notes: faire le lien entre comment elles sont appelées chez bertin et chez munzner

### Données quantitatives brutes: l'usage de la taille des symboles dans les représentations cartographiques

MAGRIT: carte monde population, nuage de points
			théorique: pourquoi pas de carte de couleur
			théorique: pourquoi des cercles proportionnels. On cherche à passer par de la taille. on représente de la donnée par pays, représentés par des polygones. C'est une marque surfacique, on ne peut pas jouer sur la taille: on passe par un symbole dérivé.
			théorique: et si on faisait autrement: nombre de symbole; cartogramme

### Au dela des cartes en symboles proportionnels

cartogramme
-> CM cartogramme et anamorphose

-> influence de la projection

### Choroplèthes

#### Le principe

CM carte choroplèthe: influence de la palette de couleur et de la méthode de classificaiton

#### Représenter des densités par de la couleur

- influence de la classification
		MAGRIT: calcul de la densité de pop
			théorique: acceptable de mapper de la densité (pop/km²; valeur/hab) sur une carte avec de la couleur, et pas de valeur brute: 2 raisons
				d'une part, la taille est le plus efficace des 2 canaux
				d'autre part, dans des données stats rattachées à des grilles geospatiales irrégulières, la valeur est souvent corrélée à la surface de la cellule: plus un pays est grand, plus il est susceptible d'être peuplé, et plus un pays est peuplé, plus une valeur corrélée à la pop peut être grandes
					si on représente une quantité brute par de la couleur, une grande région peut avoir la même couleur que plein de petites régions formant un ensemble bcp plus peuplé
					influence de la grille choisie, MAUP qui sera vu plus tard, dans 2 semaines

#### Influence de la méthode de classification

MAGRIT: carte de densité avec plusieurs modes de classification
			théorique: les différents modes de classif, et ses influences. comment bien choisir sa classif: bon tips: regarder la distribution; privilégier jenks; pas trop de classes; quantile ou quantize: dépend du contexte; parfois, seuils manuel
		- influence de la palette de couleur
		

#### Influence de la palette de couleur

théorique: influence de la palette: plusieurs teinte pour plus de classe; lien avec ce qu'il y a au dessus
		magrit: faire utiliser veridis

- influence de la palette de couleur
		théorique: influence de la palette: plusieurs teinte pour plus de classe; lien avec ce qu'il y a au dessus
		magrit: faire utiliser veridis
		MAGRIT: carte pop + birth rate
			comment représenter la couleur: sur le polygone, sur le symbole: effet, discuter de ça
			quelle paltte de couleur utiliser

- cyclique
		MAGRIT trouver données cucliue: montrer palette cyclique

## Représenter des données non-ordonnées dans MAGRIT
		
carte choroplèthe catégorisée
	- nominal
		MAGRIT carte géol: influence de la palette catégoriel
		MAGRIT sous groupes: jouer sur la teinte et les nuances de gris pour faire différenciation et association

## Présentation de Kepler.gl

## Création de cartes choroplèthes avec Kepler.gl

## Création de cercles proportionnels avec Kepler.gl	

## Création de cartes en 2D+1 


##### garder le réseau pour QGIS pour faire du glyphes


