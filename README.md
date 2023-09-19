# Projet-Long

Ce projet vise à extraire des indicateurs environnementaux à partir de données brutes ADS-B, en se concentrant sur les opérations d'atterrissage et de décollage à l'aéroport de Toulouse Blagnac.
Les principaux objectifs comprennent la fusion de ces données avec d'autres sources pour associer chaque trajectoire à un type d'avion et à ses caractéristiques techniques. 
En utilisant des techniques de data science, nous chercherons à regrouper ces données pour fournir des indicateurs sur le trafic aérien à Toulouse, notamment la distribution de l'âge des avions.
Nous envisageons également d'évaluer des hypothèses sur les consommations de carburant et le bruit produit par chaque type d'avion en nous appuyant sur la littérature disponible. 
Une attention particulière sera accordée à la classification des avions en fonction du bruit sonore, en utilisant des méthodes telles que les réseaux de neurones ou Kmeans, ainsi qu'en utilisant l'indice de performance sonore CALIPSO. 
De plus, nous prévoyons de classifier les avions par type pour calculer les émissions de polluants, en particulier le CO2.
Pour atteindre ces objectifs, nous utiliserons des outils tels que Python, Numpy, Pandas, Matplotlib, Plotly, PySpark et Streamlit pour le traitement et la visualisation des données. Le projet comprends des étapes de nettoyage, de filtrage et de recherche de bases de données à fusionner.
