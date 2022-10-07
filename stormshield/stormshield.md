# Documentation Stormshield sorti du carton

Les paramètres à utiliser sur des logiciels comme Putty, minicom ou d’autres terminaux sont les suivants :

115200 bauds, 8 bits de données N pour pas de parité, 1 bit de stop (ou 115200/8N1), pour les modèles SN160(W), SN210(W) et SN310(W), SN510, SN710, SN2100, SN3100 et SN6100.

9600/8N1, pour le modèle SN910.

- compte par défaut: admin/admin

- Se connecter sur le port 1 en RJ45 

Par défaut, le stormshield propose un DHCP en 10.0.0.10 au client et le stormshield écoute en 10.0.0.254

![](/stormshield/images/ConfIPWindows.png)

![](/stormshield/images/puttystormshield.png)

**portinfo** permet d'avoir le status des ports du stormshield.

![](/stormshield/images/portinfo.png)

L'URL d'administartion est la suivante https://10.0.0.254/admin

Compte: admin/admin

![](/stormshield/images/pageaccueilstormshield.png)

![](/stormshield/images/Accueilstormshieldauthentifié.png)

Vous verrez un message indiquant qu'il faut lui donner une licence. Vous retrouverez la licence sur le site mystormshield.eu.

Allez dans Système > Licence et installer le fichier de licence. 

## Mettre à jour un Stormshield

Aller dans Configuration > Système Maintenance et y uploader la mise à jour.

Lors de la mise à jour, il est possible d'utiliser la partition de sauvegarde si besoin de revenir en arrière (recommandé).


