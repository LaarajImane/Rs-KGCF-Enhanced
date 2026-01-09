Le modèle KGCF Enhanced (Knowledge Graph Collaborative Filtering Enhanced) est un modèle de recommandation basé sur les graphes de connaissances. Voici une explication concise de ses composants principaux :

Objectif :

Le modèle vise à améliorer les recommandations en combinant les interactions utilisateur-élément et les relations dans un graphe de connaissances.
Architecture :

UIGNNLayer : Capture les interactions utilisateur-élément.
KGGNNLayer : Exploite les relations dans le graphe de connaissances.
AdaptiveAttentionFusion : Combine les informations des deux couches précédentes en utilisant une attention adaptative.
KGCFRec : Intègre les couches ci-dessus pour produire des représentations finales des nœuds.
Entraînement :

Utilise des techniques comme le Hard Negative Sampling pour améliorer la qualité des recommandations.
Les données sont divisées en ensembles d'entraînement, de validation et de test.
Évaluation :

Les métriques comme HR@20 (Hit Ratio) et NDCG@20 (Normalized Discounted Cumulative Gain) mesurent la performance.
Avantages :

Exploite les relations complexes dans les graphes de connaissances.
Combine efficacement les informations structurelles et collaboratives.
Ce modèle est particulièrement adapté aux systèmes de recommandation nécessitant une compréhension approfondie des relations entre les entités.

