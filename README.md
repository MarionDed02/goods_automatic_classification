# Classification automatique de biens de consommation

![Capture d’écran](Images/Capture%20d’écran%202023-12-13%20à%2013.20.04.png)

## Contexte

L'entreprise "Place de marché" souhaite lancer une marketplace en ligne où les vendeurs peuvent mettre en vente leurs articles en postant une photo et une description. Cependant, il y a deux problèmes majeurs :

- La catégorisation des articles est actuellement faite manuellement par les vendeurs, ce qui entraîne une fiabilité limitée.
- Le volume des articles est encore très petit.

## Problématique

Pour améliorer l'expérience des utilisateurs (vendeurs et acheteurs) et préparer la plateforme pour un élargissement futur, il est nécessaire d'automatiser la tâche de catégorisation des articles. Cette automatisation doit se faire en utilisant à la fois le texte (description en anglais) et l'image des produits.

## Mission

En tant que Data Scientist au sein de "Place de marché", notre mission est de réaliser une étude de faisabilité pour le développement d'un moteur de classification automatisé des articles. Nous utiliserons les descriptions textuelles et les images des produits pour cela. Cela implique l'analyse des données, l'extraction de caractéristiques, et la visualisation pour évaluer la possibilité de classer automatiquement les articles. Ensuite, nous devons explorer la classification supervisée avec data augmentation pour améliorer le modèle. Parallèlement, nous testerons la collecte de produits spécifiques via une API pour évaluer l'extension possible de notre gamme de produits, avec un accent particulier sur les articles d'épicerie fine comme le champagne. Notre but est de démontrer la faisabilité de ces approches pour une mise en œuvre future.

## Données fournies

- Fichier CSV : flipkart_com-ecommerce_sample_1050.csv
- Dossier "Images" de 1050 éléments
