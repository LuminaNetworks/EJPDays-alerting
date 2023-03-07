
# EJPDays-alerting

Ce projet est un outil d'alerting pour les jours EJP en france


##### --
## Version python

Cette version python de EJPDays-alerting à pour but d'etre executer sur n'importe quel hote compatible avec python




### Fonctionnalitées

- Afficher les informations d'EJP dans la console
- Afficher les informations d'EJP dans un fichier
- Montre le nombre de jour restant et total d'EJP pour la periode en cours
- Montre la periode en cours
- Montre le jour actuel et le lendemain


### Installation

Installation d'EJPDays-alerting

```bash
  apt update
  apt install git curl wget python3 python3-pip

  git clone https://github.com/LuminaNetworks/EJPDays-alerting.git
  cd EJPDays-alerting
  chmod a+x index.py
```
    
### Affichage level

Il existe plusieur niveau d'affichage suivant le nombre d'information souhaiter :

- O : Affiche si le lendemain est un jour EJP
- 1 : Affiche le nombre de jours EJP restant au lendemain
- 2 : Affiche si aujourd'hui est un jour EJP
- 3 : Affiche le nombre de jours EJP total pour la periode en cour
- 4(default) : Affiche la periode en cour

tips: Le niveau d'affichage affichera toujours les niveaux inferieurs
(ex: si le niveau d'affichage est régler sur 2, sera afficher les niveaux 2/1/0)
### Utilisation/Exemples

Affichage dans la console
```python
  cd EJPDays-alerting/linux 
  python index.py
```

Affichage dans un fichier
```python
  cd EJPDays-alerting/linux 
  python index.py -o output.txt
```

Utilisation du niveau d'affichage
```python
  cd EJPDays-alerting/linux 
  python index.py -l 3
```
### Démonstration

Insert gif or link to demo

