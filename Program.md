# ANF 2023 OMERO-FAIRly
# Programme

## Jour 1 - matin : introduction
- Presentation de la formation
- Introduction des participants : table ronde
- La science ouverte : Intervenant Jason Swedlow
- Principes FAIR : Intervenant ?
- Introduction a OMERO : histoire du projet

## Jour 1 - apres-midi : démarrer avec OMERO
- OMERO import images
- Details on import : 
  - MDE
  - in-place import
  - CLI import
  - OMERO.smuggler
- Manage images (panneaux gauche) :
  - Create Datasets and Projects
  - Move images between Datasets and Projects
  - Delete data
  - ...
- Visualize images : OMERO.iViewer
- Create ROIs

## Jour 2 - matin : meta-donnees
- OMERO infrastructure
  - Deployment : Intervenant Guillaume Gay
- Metadata (panneaux droit)
- Data annotation
  - Description
  - Tags
  - Key-value pairs
  - Tables
- Search
- Browse measurements : OMERO.parade

## Jour 2 - apres-midi : collaborer
- Groupes collaboratifs et droits d'access
- Gestion de groupes
- Practices de gestion de groupes en plateforme
- Make figures for publication : OMERO.Figure

## Jour 3 - matin : analyser
- ImageJ OMERO plugin
- ImageJ macros
- ImageJ scripts
- Other tools : Cellprofiler, Ilastik, ...

## Jour 3 - apres-midi
- Other analysis scenarios
  - Deployment des analyses dans l'IFB : intervenant Christophe Blanchet
  - Python notebooks
- Future of OMERO (NGFF) : intervenant Josh Moore
- Cloture


L’ensemble des exercices s’effectue sur le serveur de démonstration.

https://bioimage.france-bioinformatique.fr/demo-mri
Session 1
Exercice 1 : télécharger une image sur le serveur
    1. Télécharger la version d’OMERO insight compatible avec le serveur de démonstration.
    2. Installer OMERO insight
    3. Vérifier les paramètres de connexion
bioimage.france-bioinformatique.fr/??? port ???
(logging et mots de passe distribués)
    4. Connecter OMERO-insight au serveur en utilisant les identifiant et mot de passe pour la formation
    5. Télécharger une image sur le serveur en créant un nouveau Project et un nouveau Dataset.
Exercice 2 : visualiser une image sur l’interface web
    1. Ouvrir l’image que vous venez d’importer dans omero-iviewer
    2. Explorer l’image (si applicable : visualiser les différents canaux, les différents plans en z, le temps…)
Exercice 3 : visualiser des images
    1. Parcourir les images du dataset 'Adjust rendering settings’
    2. Visualiser les histogrammes des niveaux de gris
    3. Ajuster les niveaux de gris
    4. Copier et appliquer à l’ensemble des images du même dataset les ajustements des niveaux de gris
    5. Copier et appliquer à une partie des images les ajustements des niveaux de gris.
Exercice 4 : comparer deux images
    1. Ouvrir dans omero-iviewer deux images du dataset ‘Viewing’
    2. Les comparer
Session 2
Exercice 1 : Tagger les images du dataset ‘Annotations and searching’ avec l’outil ‘autotag’
Exercice 2 : Chercher à sélectionner, avec l’outil ‘Tag Search’, des images par rapport aux tags que vous avez ajouté. Vous pouvez aussi, essayer de tagger les datasets et projects. Est que vous pouvez voir et tagger les images des autres ?
Exercice 3 : Chercher des images spécifiques en utilisent le moteur de recherche. Essayer de filtrer les résultats pour montrer vos images à vous ou à d’autres collègues. Utiliser des ‘wild cards’ ou caractères ‘joker’ pour flexibiliser votre recherche. Utiliser des combinateurs logiques (AND OR) pour rendre les recherches plus complexes.
Exercice 4 : Les images dans le dataset ‘Annotations and searching’ ont des annotations ‘key-value pairs’. Regardez-les et essayez de trouver des images d’intérêt. Essayez de trouver des images avec des mesures dans un tranche de valeurs avec des valeurs spécifiques avec la syntaxe my_key:0.3. Est-ce que vous trouvez une image ? Pourquoi ? Essayez avec my_key:[0.2 TO 0.4]

Session 3
Exercice 1 : Publication
    1. Sur une image z-stack ou un time lapse, créer un export vidéo du z-stack avec 1 image par seconde
    2. Sur des images possédant un tag, créer un thumbnail
    3. Sur deux images possédant un tag, et ayant les mêmes dimensions (xyzct), créer un split view figure dont les trois canaux.
Exercice 2 : Figure
    1. Créer une figure pour comparer une image SIM d’une image champ plein, avec une vue globale et un zoom pour chacun des canaux ainsi que sa combinaison, les barres d’échelle, les noms des canaux
    2. Créer une figure avec les images de votre choix



Session 4
Exercice 1 : Interaction avec Fiji
    1. Suivez les instructions pour installer le plugin OMERO pour FijI
    2. Se connecter à OMERO et ouvrir une image de OMERO avec FijI
    3. Créer deux ROIs: rectangle et une d’un autre type et les ajouter sur le ROI manager
    4. Faire une mesure d’intensité sur chacune des ROIs
    5. Sauver les ROIs et les mesures sur OMERO.

Les liens
Le site du Open Microscopy Environment https://www.openmicroscopy.org
Le mode d’emploi https://omero-guides.readthedocs.io
YouTube Channel https://www.youtube.com/channel/UCyySB9ZzNi8aBGYqcxSrauQ/videos
L’adresse du serveur OMERO de MRI : https://omero.mri.cnrs.fr
Votre identifiant et votre mot de passe sont ceux créés pour l’utilisation des ressources MRI.
Contacter un ingénieur MRI pour le management d’un groupe : création d’un groupe, ajout d’une personne…
Si vous avez une question sur OMERO, vous pouvez envoyer un mail à omero@mri.cnrs.fr.



