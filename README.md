# [SQUARE](https://www.github.com/lafelabs/square)

## [LOCALHOST](http://localhost/)

## [WWW.TRASHROBOT.ORG](https://www.trashrobot.org)

A 4 INCH SQUARE OF CARDBOARD!

FREE STUFF!

TRASH MAGIC!

![](https://raw.githubusercontent.com/LafeLabs/square/main/trashmagic/qrcode.png)

![](https://raw.githubusercontent.com/LafeLabs/square/main/trashmagic/trashmagic.png)

![](https://raw.githubusercontent.com/LafeLabs/square/main/trashmagic/sloanslakedotart.png)


TO REPLICATE THE TRASH MAGIC SERVER, GET A COMPUTER FROM THE TRASH AND WIPE THE HARD DRIVE AND INSTALL [UBUNTU](https://ubuntu.com/desktop) OR SOME OTHER KIND OF LINUX.  THEN REPLICATE THE TRASH MAGIC SERVER BY INSTALLING [APACHE](https://www.apache.org/) AND [PHP](https://www.php.net/), COPYING AND RUNNING THE REPLICATOR SCRIPT [REPLICATOR.PHP]!  

```
sudo apt update
sudo apt install apache2 -y
sudo apt install php libapache2-mod-php -y
cd /var/www/html
sudo rm index.html
sudo apt install curl
sudo curl -o replicator.php https://raw.githubusercontent.com/LafeLabs/square/main/php/replicator.txt
cd ..
sudo chmod -R 0777 *
cd html
php replicator.php
sudo chmod -R 0777 *
```

THEN GET A GENERIC DOMAIN REPRESENTING A PHYSICAL GEOGRAPHIC FEATURE OF WHERE YOU ARE IN PHYSICAL SPACE, AND POINT THAT DOMAIN TO YOUR HOME IP, FORWARDING PORT 80 TRAFFIC TO THE SERVER!

WRITE THE DOMAIN ON THE SQUARES AND DISTRIBUTE THEM! 

EDIT THE SELF-REPLICATING SET AND REPLICATE IT BACK OUT ACROSS THE NETWORK FROM SERVER TO SERVER, ALWAYS LINKING TO NEW SERVERS AS THE NETWORK GROWS!

USE THIS FREE MEDIA ON TRASH SERVERS TO SPREAD FREE THINGS MADE FROM TRASH!

USE SQUARES TO FABRICATE CUBES AND USE CUBES TO BUILD A WHOLE NEW WORLD!
