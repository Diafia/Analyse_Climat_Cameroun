# Analyse_Climat_Cameroun
Étude exploratoire en Data Science examinant la vulnérabilité climatique du Cameroun face à sa faible contribution aux émissions de CO₂. Inclut une comparaison avec l'Afrique et une analyse de clustering (K-Means).


# 1. Contexte du Projet
Ce projet explore, via une approche Data Science, le concept de "Double Fardeau Climatique" appliqué au Cameroun sur la période 1970-2023. Il met en lumière l'inégalité climatique : celle où les pays à faible empreinte carbone sont paradoxalement les plus vulnérables aux changements climatiques mondiaux.

L'analyse se focalise sur deux axes majeurs : la responsabilité (émissions de CO₂) et la vulnérabilité (hausse des températures).

# 2. Objectifs de l'Analyse
Quantifier l'Inégalité : Comparer l'évolution des émissions de CO₂ par habitant du Cameroun par rapport à la moyenne mondiale.

Mesurer l'Impact : Visualiser la tendance de l'augmentation des températures moyennes nationales et l'analyser au niveau régional (si des données de villes/régions ont été incluses).

Contextualiser en Afrique : Utiliser des techniques de Machine Learning pour positionner le profil climatique et d'émissions du Cameroun au sein de l'Afrique subsaharienne.

# 3. Données Utilisées
Le notebook intègre et nettoie des données issues de sources fiables :

Température : Datasets d'anomalies et de moyennes de températures mondiales et régionales (Source : Berkeley Earth / NASA GISS).

Émissions de CO₂ : Indicateurs d'émissions de CO₂ par habitant (Source : Banque Mondiale).

# 4. Méthodologie
Nettoyage et Ingénierie des Caractéristiques : Alignement des séries temporelles (1970-2023) et fusion des données.

Visualisation Exploratoire (EDA) : Courbes d'évolution comparées (Température et CO₂) pour établir le contraste mondial.

Apprentissage Non Supervisé : Application de l'algorithme de K-Means sur les indicateurs de vulnérabilité et de responsabilité pour le clustering des pays africains.

# 5. Résultats Clés
L'analyse confirme :

Le Cameroun se situe dans un cluster de pays caractérisés par une vulnérabilité élevée aux impacts climatiques et une très faible émission de CO₂.

L'écart entre la faible responsabilité et l'impact sévère est amplifié par des facteurs endogènes (dépendance économique, lacunes de gouvernance).
