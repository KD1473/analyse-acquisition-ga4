# Analyse de l'acquisition : Google Merchandise Store (GA4)

**Contexte**
Le Google Merchandise Store est une boutique en ligne qui vend des vêtements
et des accessoires de marque Google. Les données GA4 sont anonymisées et
couvrent environ 3 mois (nov. 2020 à janv. 2021).

**Question business**
Quels canaux d'acquisition (source / support) génèrent le plus de
conversions et de chiffre d'affaires, et lesquels méritent plus ou
moins d'attention ?

**Pourquoi c'est important**
Cette analyse aide une équipe marketing à décider où concentrer ses efforts
d'acquisition. Limite assumée : le jeu de données ne contient pas les coûts
publicitaires, donc je mesure la performance des canaux, pas leur ROI.

**Données utilisées**
BigQuery, dataset public `ga4_obfuscated_sample_ecommerce`
(tables `events_*`) : sessions, sources de trafic, événements d'achat.

**Livrables**
Requêtes SQL (ce dépôt), dashboard Power BI, page de cas avec recommandation.
