# PHY-2006: Optique expérimentale Projet 1
Bienvenue dans le dépôt Github du cours PHY-2006: Optique expérimentale. Ce dépôt contient le projet expérimental (PE) #1 en Jupyter Notebook dans lesquelles le code est écrit en language Python.

## Aperçu du contenu
Le dépôt est organisé en plusieurs fichiers, chacun contenant les notebooks pour un des deux PE. Le premier PE couvre majoritairement l'analyse d'image alors que le second reste toujours à déterminer.

Le nom de chaque fichier est formaté comme suit: **PE#_Nom_du_projet**. Chaque fichier contient également des cellules de Markdown énonçant les étapes de résolutions.

## Comment utiliser les notebooks
Pour utiliser les notebooks, vous devrez avoir Jupyter Notebook installé sur votre ordinateur. Vous pouvez installer Jupyter Notebook à partir de la ligne de commande en utilisant la commande suivante:

```python
pip install jupyter
```

Une fois installé, vous pouvez naviguer vers le fichier du PE que vous souhaitez utiliser et exécuter le code.

L'utilisation du code est très simple. Vous devez d'abord insérer votre dossier contenant vos images et le nommer **Measures_Laser_Name** où **Laser_Name** est le nom de votre laser. Insérez ensuite les trois lignes ci-dessous dans une nouvelle boîte de code à la fin du notebook Jupyter et interprétez celle-ci.

```python
plot_images("Images/Measures_Laser_Name", laser="Laser_Name")
plot_intensity_profile("Images/Measures_Laser_Name", laser="Laser_Name")
distance("Images/Measures_Laser_Name", laser="Laser_Name")
```

## Contribution
Si vous souhaitez contribuer à ce dépôt, veuillez ouvrir une issue ou envoyer une demande de fusion. Toutes les contributions sont les bienvenues, y compris les corrections de bug et les améliorations de code.

## Auteurs
Ce dépôt est maintenu par les membres de l'équipe d'étudiants surdoués du cours PHY-2006: Optique expérimentale à l'Université Laval. Les auteurs individuels pour chaque PE sont répertoriés en préambule de chaque fichier.
