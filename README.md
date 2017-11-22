# LINUX DOC

ifconfig   - reg des  config et ip adresse 

Linux - Compresser/Décompresser un fichier ZIP :
Pour compresser un ensemble de fichiers, l'usage est le suivant : 
zip -r nom_du_fichier.zip repertoire_ou_fichier  /  zip -r nom_de_larchive.zip dossier  /  
zip -r nom_de_larchive.zip dossier-a-ziper

Pour décompresser un fichier, l'usage est le suivant :
unzip nom_du_fichier.zip -d destination



## Linux - commandes fondamentales


### La navigation :

cd / Permet de se retrouver à la racine du disque.

cd ~ ou cd Accéder directement au répertoire de l’utilisateur.

cd /var/www/ Aller dans le répertoire /var/www.

cd .. Remonter dans le répertoire parent à partir de là où vous êtes.

cd - Permet de revenir au répertoire précédent.

pwd Renvoyer le chemin absolu du répertoire courant ce qui est utile puisqu’en général le shell


### Afficher le contenu d'un répertoire :

ls -l Afficher les informations de manière détaillée.

ls -a Afficher les fichiers cachés.

ls -h Afficher la taille des fichiers de facon lisible.

ls -r Tri inversé.

ls -t Trier les fichiers par date du plus récent au plus ancien.

ls -S Trier par taille décroissante.

ls -la Afficher tous les fichiers y compris les fichiers cachés.

ls -lhS Afficher les informations des fichiers, avec des tailles lisibles le tout ordonné du plus grand au plus petit.


### Un fichier

Créer un fichier : touch fichier.txt

Editer un fichier : vi fichier.txt     > i ( edition) > Echap:wq ( subegarde)

Renommer le fichier test.txt en test2.txt : mv test.txt test2.txt

Supprimer : rm fichier.txt




