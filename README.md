<p align="center">
<a href="https://hits.seeyoufarm.com"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FUpDev%2FBlueFramework-View&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/></a>
<img alt="Discord" src="https://img.shields.io/discord/1046385496324051014?label=Discord&color=%25235865f2">

<img alt="GitHub" src="https://img.shields.io/github/license/UpDev/BlueFramework-View">

</p>


# 🪓 Gamemode pour Fivem

# 📌 Requirements

- [oxmysql](https://github.com/overextended/oxmysql/)

```
✔️ Oxmysql est une alternative aux ressources mysql-async/ghmattimysql non maintenues, utilisant node-mysql2 plutôt que mysqljs .
```

# 📝 Install

- Installer le framework et glissé-le dans le dossier ```ressources```
- Installer oxmysql et glissé-le dans le dossier ```ressources```
- Insérer le sql en ```Base de donnée```
- Tout ce qui est à start est à mettre dans le ```server.cfg```

```
ensure oxmysql
ensure BlueFramework
```

- Liaison à la Base de donnée

```
set mysql_connection_string "mysql://root@localhost:3306/blueframework?waitForConnections=true&charset=utf8mb4"
```

# 📍 Inclus

  - Videos: a venir
  - Tout Systéme est Synchro au client
  - Pour voir l'inventaire appuyer sur la touche ```f5```
  
 ```GESTION JOUEUR```
 
 - Création Joueur en ```BDD```
 - Systéme d'argent
 - Systéme d'add tout type d'argent (money,black_money,bank)
 - Systéme de remove tout type d'argent (money,black_money,bank)
 - Systeme d'identité
 - Systeme de skin et de vetement
 - Spawn derniére positions


 ```GESTION INVENTAIRE```
 
 - Systéme de poids
 - Systéme d'item
 - Systéme d'add item
 - Systéme de remove item

 ```GESTION JOB```
 
 - Systéme de Job
 - Systéme de setjob
 - Systéme de Crew
 - Systéme de setcrew
 
  ```GESTION RANK```
 
 - Systéme de Rank
 - Systéme de setrank

# 🔓 Commande Inclus
  
  - Add Item
  
  ``` /giveitem id item count```
  
  - Remove Item
 
  ``` /removeItem id item count```
  
  - Add Money

  ``` /addmoney id account count```
  
  - Remove Money
  
  ``` /removemoney id account count```

  - Set Licenses (drive_truck, dmv, drive, drive_bike, weapon)
  
  ``` /setlicenses id license 0 or 1```

  - Set Job

  ``` /setjob id job grade```

  - Set Crew

  ``` /setcrew id crew grade```
  
  - Set Rank (Utilisable uniquement console server)

  ``` /setrank id rank```

  - Spawn Car

  ``` /car model```

  - Information Joueur (Affiche les information du joueur a partir de la base de donnée)

  ``` /info```

  - Coords

  ``` /coords```

  - Revive

  ``` /revive```

  - Id (Affiche votre id)

  ``` /id```

  - Sync (force update de vos information en bdd)

  ``` /sync```

  - Stuck (te téléporte sur une position si tu es bloquer)

  ``` /stuck```

  # 🩸 IMPORTANT
  
 **Je ne recommande pas ce framework au débutant . Pour continuer ce framework il est néccéssaire d'avoir des connaissances en programation .Pour toute aide je vous invite à rejoindre le discord:**
 
  # 📈 Support
  
  - [Discord](https://discord.gg/p49CNewUC9)

