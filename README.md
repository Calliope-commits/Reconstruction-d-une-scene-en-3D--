# Reconstruction-d-une-scene-en-3D--

Unviersité Paris Cité - 2022 - Reconstruction 3D - Enseignant : Ewelina Rupnik

## Description

Dans le cadre de notre cours de 3D il nous a été demandé de réaliser la reconstruction d’une scène en utilisant la photogrammétrie. Cette technique permet d'effectuer des mesures à partir d’une série d’images d’une scène choisie. En superposant ces images nous pouvons obtenir un modèle 3D à l’aide d’un certain nombre d’algorithmes. 

Les étapes de réalisation de notre projets sont:

● Choisir un objet 3D ou une scène : dans notre cas nous avons utilisé un objet 3D 

● Prendre une série d’image de l’objet : 74 images pour notre projet 

● Utiliser un logiciel de notre choix pour réaliser deux types de reconstruction :

    - Structure from motion: donne une représentation éparse de l’objet (Sfm) 
    
    - Multiview surface: donne une représentation dense de l'objet (Mvs) 

Nous avons utilisé le logiciel MicMac 

## Choix de l'objet : 

Nous avons utilisé la sculpture d’un panier de fruits sur une table en bois. Puisque les deux éléments présentent de la texture ainsi que des patterns, MicMac a pu détecter des tie points. (figure 3 et 4)

![image](https://github.com/Calliope-commits/Reconstruction-d-une-scene-en-3D--/assets/61286710/988ec6fb-00f1-49aa-9702-c08678b03b77)


## Reconstruction éparse 
Dans notre dossier, ce fichier est intitulé Panier_Sfm.ply.
Sur les figures 6 7 et 8 nous avons 323479 sommets


![image](https://github.com/Calliope-commits/Reconstruction-d-une-scene-en-3D--/assets/61286710/026781f0-b2bf-4e9e-8415-21d38c79b3f6)

![image](https://github.com/Calliope-commits/Reconstruction-d-une-scene-en-3D--/assets/61286710/63b279d0-dee6-40d5-aa37-00a8c5ea5d66)


## Reconstruction dense 

MicMac permet également la reconstruction dense d’un objet en 3D à partir d’un nuage de point éparse : c’est l’outil C3DC, Culture 3D Cloud. Il permet la création d’un nuage de point , toujours au format .ply par corrélation multi stéréoscopique dense. Dans notre dossier ce fichier est intitulé Panier_Mvs.ply. Nous pouvons également varier la taille du point pour obtenir une différente représentation.


![image](https://github.com/Calliope-commits/Reconstruction-d-une-scene-en-3D--/assets/61286710/c2c8b7af-bc80-4f08-ba05-72c29534583e)

![image](https://github.com/Calliope-commits/Reconstruction-d-une-scene-en-3D--/assets/61286710/bda9a343-84e1-487c-a11f-882ef3ccb41d)

Pour cette représentation dense (figure 9, 10, 11 et 12), nous affichons 285033 sommets.
