# ROBO2_Navigation_Ramcharn_ShamYu_Ramanantenasoa
### Navigation (Partie 1)
Le but de ce TP est de créer un noeud pour envoyer des positions au Turtlebot.

#### Pour l'utiliser,  

```sh
git clone https://github.com/MimRamcharn/ROBO2_Navigation_Ramcharn_ShamYu_Ramanantenasoa.git
```
- Ouvrez un terminal et faites "roscore", dans un autre terminal "ssh ubuntu@adresse_ip" et "roslaunch turtlebot3_bringup turtlebot3_robot.launch"
- Ouvrez votre carte sur RViz et à l'aide du bouton '2D Pose Estimate", faites glisser la flèche verte vers 3 positions.
- Pour avoir les coordonnées de ces positions, ouvrez un terminal et tapez la ligne suivante "rostopic echo /initialpose "
- Dans le fichier "goto.py", modifier les valeurs de "x" et "y" des 3 positions.
- Lancer le noeud et surveiller la trajectoire du robot sur RViz.