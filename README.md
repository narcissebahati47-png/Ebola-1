Recensement Ebola RDC 2026 — Étude Cas-Témoins (Données fictives)

Données entièrement simulées à but pédagogique et démonstratif. Aucun participant, aucun cas et aucune donnée de ce fichier ne correspond à des personnes ou événements réels. Ce jeu de données a été construit pour illustrer une méthodologie d'étude cas-témoins en épidémiologie, appliquée ici au contexte de la maladie à virus Ebola.

Description

Ce dépôt contient un jeu de données simulé reproduisant une étude cas-témoins menée en République Démocratique du Congo (RDC) sur une épidémie fictive de maladie à virus Ebola, entre le 15 mai et le 31 juillet 2026.

L'objectif est d'illustrer :

· la structure d'un recensement cas-témoins en contexte d'épidémie ;
· le calcul et l'interprétation d'odds ratios (OR) pour identifier des facteurs de risque et de protection ;
· la construction d'un tableau de bord de surveillance épidémiologique.

Structure du fichier

Le fichier « recensement_ebola_rdc_2026_cas_temoins.xlsx » contient 5 feuilles.

La feuille « Recensement » présente les données individuelles brutes des 180 participants, avec 22 variables.
La feuille « Synthese » regroupe les indicateurs clés agrégés et la répartition géographique par province.
La feuille « Dictionnaire_Variables » décrit chaque variable, sa signification et son format.
La feuille « Analyse_Statistique » contient les tableaux de contingence 2x2 et les odds ratios avec leurs intervalles de confiance à 95 % pour trois expositions.
Enfin, la feuille « Dashboard » offre un tableau de bord synthétique de surveillance.

Aperçu des données

L'étude comprend 180 participants au total, répartis en 60 cas (dont 58 confirmés positifs en RT-PCR) et 120 témoins. La répartition géographique couvre les provinces de l'Équateur, de l'Ituri, du Nord-Kivu et du Sud-Kivu.

Parmi les cas, l'issue clinique se répartit comme suit : 21 décès, 30 guérisons et 9 personnes encore en cours de suivi. La létalité parmi les cas confirmés s'élève à 36,2 %. L'âge moyen des participants est de 29,7 ans (29,4 ans pour les cas et 29,8 ans pour les témoins). La répartition par sexe est équilibrée, avec 50 % de femmes.

Variables du recensement

Chaque ligne de la feuille « Recensement » correspond à un participant et inclut notamment les informations suivantes :

· Identifiants : ID patient, nom complet (fictif), statut dans l'étude (cas ou témoin).
· Données démographiques : âge en années, sexe, province, zone de santé, aire de santé, profession.
· Expositions évaluées : contact avec un cas confirmé dans les 21 jours précédents, présence à un enterrement à risque, distance au centre de santé en kilomètres, statut vaccinal contre Ebola.
· Signes cliniques : fièvre, vomissements, diarrhée, signes hémorragiques.
· Issues : résultat de la RT-PCR, issue clinique, date de sortie, guérison ou décès.

Le détail complet de chaque variable, avec sa description et ses modalités, est disponible dans la feuille « Dictionnaire_Variables ».

Résultats de l'analyse statistique (odds ratios)

Trois expositions ont été analysées à l'aide de tableaux de contingence 2x2.

Le contact avec un cas confirmé dans les 21 jours précédents présente un odds ratio de 6,67, avec un intervalle de confiance à 95 % allant de 3,35 à 13,3. Ce résultat indique un facteur de risque, avec une association statistiquement significative.

La participation à un enterrement à risque donne un odds ratio de 5,38, avec un intervalle de confiance à 95 % compris entre 2,06 et 14,07. Là encore, il s'agit d'un facteur de risque avec une association significative.

Enfin, le statut vaccinal anti-Ebola (vaccin rVSV-ZEBOV) montre un odds ratio de 0,77, avec un intervalle de confiance à 95 % allant de 0,35 à 1,68. Bien que l'effet soit suggéré comme protecteur, il n'est pas statistiquement significatif car l'intervalle inclut la valeur 1.

Lecture des résultats

Un odds ratio supérieur à 1 signifie que l'exposition est associée à un risque accru d'être un cas (facteur de risque potentiel).
Un odds ratio inférieur à 1 indique que l'exposition est associée à un risque réduit (facteur protecteur potentiel).
Si l'intervalle de confiance à 95 % inclut la valeur 1, l'association n'est pas statistiquement significative au seuil de 5 %.

Dashboard

La feuille « Dashboard » propose une vue de synthèse rapide, avec le total des inclus, le nombre de cas, de témoins, de décès, le taux de létalité, ainsi que des graphiques pour une visualisation immédiate.

Utilisation

Ce jeu de données peut être utilisé pour :

· s'entraîner à l'analyse épidémiologique, notamment le calcul d'odds ratios et d'intervalles de confiance ;
· réaliser des démonstrations de nettoyage et de visualisation de données avec Excel, Python ou R ;
· servir de support pédagogique pour l'enseignement des études cas-témoins en santé publique.

Avertissement

Ces données sont entièrement fictives. Elles ne doivent en aucun cas être utilisées comme source d'information épidémiologique réelle, ni être citées comme documentant une épidémie réelle de maladie à virus Ebola en RDC.
