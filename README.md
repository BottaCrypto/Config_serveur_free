# Config_serveur_free

Installation des dépendances:
>sudo apt-get update  

>python3 --version  

>sudo apt install python3-pip 

Installation du bot:
>git clone live-branch https://github.com/CryptoRobotFr/cBot-Project.git  

>sudo apt install python3  

>pip install testresources  

>pip install packaging  

>pip install -r requierements.txt  

Lancer le bot toute les heures:
>crontab -e  

>0 * * * * python3 cBot-Project/live_strategy/big_will_v2_live.py >> cronlog.log  

>crontab -1  

>nano cronlog.log  

Vérifier que le bot fonctionne:
>python3 cBot-Project/live_strategy/big_will_v2_live.py  
