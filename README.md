# Description :
L'algorithme de Floyd-Warshall est utilisé pour trouver les plus courts chemins entre tous les pairs de nœuds dans un graphe pondéré avec des arêtes de poids positif ou négatif. 
L'algorithme de Floyd-Warshall a une complexité de temps de O(V^3), où V est le nombre de nœuds dans le graphe. Cela en fait une méthode efficace pour de petits graphes ou des situations où la matrice d'adjacence est dense.

Utilisation de l'algorithme de Floyd-Warshall pour calculer toutes les paires de chemins les plus courts dans un graphe routier extrait d'une zone géographique spécifique à l'aide d'OSMnx et NetworkX. Ensuite, le trace d'un itinéraire entre deux points donnés sur une carte interactive avec Folium.
# Bibliothèque utilisée : 
## OSMnx (OpenStreetMap):

Utilisation : Extraction de données géographiques à partir d'OpenStreetMap (OSM) et création de graphes routiers.

Fonctionnalités : Téléchargement de données OSM, création de graphes basés sur des données géographiques, extraction de nœuds et d'arêtes, calcul de chemins et distances.

## NetworkX :

Utilisation : Bibliothèque Python pour la création, la manipulation et l'étude de la structure, de la dynamique et des fonctions de réseaux complexes.

Fonctionnalités : Implémentation de l'algorithme de Floyd-Warshall pour calculer les chemins les plus courts, manipulation de graphes, calculs de chemins et distances.

## Matplotlib :

Utilisation : Bibliothèque de visualisation pour créer des graphiques statiques, notamment des tracés de graphes et des représentations de données.

Fonctionnalités : Tracé des graphes, personnalisation des graphiques, ajout d'annotations.

## Folium :

Utilisation : Bibliothèque Python pour la création de cartes interactives et dynamiques.

Fonctionnalités : Création de cartes web interactives, ajout de marqueurs, de polygones et de lignes, personnalisation de la carte.
