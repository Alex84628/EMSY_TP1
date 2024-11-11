# EMSY - TP1 - 2024 - 2025
## Infos Pratique - Bonne pratique git

	
  	exemple ligne de commande 
	
//accéder à la racine :

cd /

//avoir les permissions 

sudo

//acéder au répértoire home :

cd /home

//créer un répértoire :

sudo mkdir nomDurepertoire

//créer un fichier :

sudo vi nomDuFichier

//télécharger text mode :

sudo sparkylinux -installer

//pour quitter la machine virtuel :

sudo shutdown

//pour avoir le clavier suisse

sudo loadkeys fr_CH

//détérminer le pourcentage de la swap :

cat /proc/sys/um/swappiness

//observer les différente partition

lsblk -f

//verifié si nano est instalé ou connaitre sa version :

nano --version

//verifié si git est instalé ou connaitre sa version :

git --version

//pour instaler git 

sudo apt install git

//si apt pas à jours

sudo apt update

//s'attribuer la propriété dans un répértoire :

sudo chown $USER : $USER /nomDuRepertoire

//appliquer les permissions de lecture, ecriture et execution :

chmod 700 /nomDuRepertoire

//voir les permissions ou information des repertoire

ls - ld

//pour clone un git

git clone (lien du git)

//ouvrir le fichier source.c :

nano source.c

//enregistrer le fichier :

ctrl + o

//quitter le fichier :

ctrl + x :

//verifié si le compilateur est instalé ou connaitre sa version :

gcc --version

//pour push sur github

cd C:\AlexandreRabaldProgramation\EMSY\EMSY_TP1
git add -A
git commit -m "MAJ fichier.c"
git push

 **[aide pour créer un readme](https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#GitHub-flavored-markdown)**
