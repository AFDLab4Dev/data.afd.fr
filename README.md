# data.afd.fr
Ce dossier contient les applications web et code source python pour maintenir le portail data de l'AFD

**Production des Dataviz:**
Les dataviz sont produites via un script ipython: 
- [Dataviz for dev builder](Dataviz%20for%20dev%20builder.ipynb)
- Les paramètres/instructions de production de chaque dataviz sont écrits dans un fichier json: [dataviz_production.json](dataviz_production.json)
- A faire: précedemment les json de Gallup étaient organisées par Variables (une variable par fichier) contrairement aux autres organisés par pays (un fichier par pays). Désormais pour faciliter la création de dataviz les json contenant les donnés Gallup sont au même format que les autres. Il reste cependant à adapter le script de production des dataviz Gallup (voir Dataviz for dev builder.ipynb)

**Extraction / préparation des données:**
Les données qui nourrissent les dataviz sont des fichiers JSON. Ils sont créés à partir de differents scripts, un par source de données.
Les scripts pytons utilisent les bases de données téléchargés sous format csv ou xls. 
- Traitement des [World Development Indicators](WDI%20from%20unique%20CSV%20file%20v2.1%20May%202017.ipynb)
- [World Economic Outlook](IMF%20WEO%20from%20Excel%20-%20v2.1%20%20May%202017.ipynb)
- [Gallup world poll](Gallup%20-%20Creating%20a%20Json%20Database%20JSON%20%20V5%2023%20avril%202017.ipynb)

**Production des country dashboards:**
Les pages country dashboards sont produites par une script python: [Dashboard ISO frame](Dashboard%20ISO%20frame.ipynb)


## Site map / organisation
