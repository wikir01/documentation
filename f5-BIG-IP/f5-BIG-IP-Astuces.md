Comment avoir une configuration commune à plusieurs déploiement de f5:

Installer et configurer son f5 tel qu'on le souhaite, se connecter en SSH et tapez :

`save sys config file <file name.scf>`

Puis éditer le fichier pour ne conserver que les informations communes aux autres déploiements.

bigtop -vname -delay 1 -vips 100 -delta