# stats-descriptives-depenses-sante
projet de statistique descriptive univariée sur les dépenses de santé par habitant, pays OCDE

## Objectif
Analyse univariée des dépenses de santé par habitant dans 38 pays de l'OCDE, afin de caractériser la distribution (tendance centrale, dispersion, forme, valeurs atypiques) d'une variable économique du secteur de la santé.
 
## Source des données
OCDE, *Health expenditure and financing*, dépenses de santé par habitant (€ PPA), dernière année disponible.
[data-explorer.oecd.org](https://data-explorer.oecd.org)
 
## Méthode
- Mesures de tendance centrale : moyenne, médiane, mode
- Mesures de dispersion : écart-type, variance, étendue, coefficient de variation
- Forme de la distribution : asymétrie (skewness), aplatissement (kurtosis)
- Détection des valeurs atypiques : règle de Tukey (bornes = Q1 − 1,5×IQR et Q3 + 1,5×IQR)
- Visualisations : histogramme , diagramme à barres, boîte à moustaches
Outil utilisé : Excel 
 
## Résultats clés
| Indicateur | Valeur |
|---|---|
| N | 38 pays |
| Moyenne | 3 885,1 € |
| Médiane | 3 567,4 € |
| Écart-type | 1 733,7 € |
| Coefficient de variation | 0,45 |
| Asymétrie (skewness) | 0,91 |
| Kurtosis (excess) | 2,18 |
| Borne haute (Tukey) | 8 630,2 € |
 
La distribution est asymétrique à droite : la moyenne dépasse la médiane, et l'application de la règle de Tukey identifie un unique outlier statistique, les **États-Unis** (9 776,5 €), à plus de 3000 € du deuxième pays le plus dépensier (Suisse, 6 562,1 €).  

## Contenu du dépôt
- `stats_descriptives_depenses_sante.xlsx` : fichier Excel complet (données, calculs, graphiques)
