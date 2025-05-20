L'objectif de ce T.P. est de réaliser en équipe, à l'identique la page de jeu (voir en bas de la page) en HTML / php.

Des personnages tous différents, avec ou sans :

Lunettes
Moustaches
Chapeau
Cheveux.
Combien de personnages y-a-t-il ? Réponse --> 2^4 = 16

Combien faut-il poser de questions pour être sûr de pouvoir trouver le bon personnage ? Réponse --> quatre questions.

Question : Quel est le nombre minimal de différences entre deux personnages quelconques ?

Programmez sous Apache en php le jeu : "qui est-ce ? " Il est demandé par groupe de travail :

un lien vers le compte rendu du T.P. sur le Wiki (un seul par groupe) un lien sur le site de chaque étudiant (le jeu en ligne, équivalent au lien donné en bas de page) un lien github avec votre code (un seul par groupe).

Il ne faut pas oublier de réaliser un Gantt (vous pouvez utiliser par exemple ganttproject (de préférence) https://www.ganttproject.biz/download ) ou tout simplement Excel (ou équivalent).

Le codage des personnages : de la gauche vers la droite. des lunettes 1 pas de moustache 0 un chapeau 1 des cheveux 1 pas de boucle d'oreille 0 une barbe 1 pas de noeud papillon 0

1011010
Codage en binaire --> Lunettes – moustache – chapeau – cheveux – boucle d’oreille – barbe – nœud papillon

Compléments : Merci Thomas :

pour lancer lampp : sudo /opt/lampp/lampp start
pour arrêter lampp : sudo /opt/lampp/lampp stop
pour installer lampp : sudo ./xampp-linux-x64-8.2.4-0-installer.run
et encore :

services lampp stop
chemin d'apache /opt/lampp/htdocs/
ps -ax|more (liste des processus) kill -9 N° Processus - pour terminer le processus. sudo /etc/init.d/apache2 stop

Le XAMPP Control Panel vous permet de lancer à la fois votre serveur Web et votre base de données. Il est très facile d'ouvrir l'interface Web de phpMyAdmin dans le navigateur de votre choix. Pour ce faire, entrez l'adresse : «http://localhost/phpmyadmin» dans la barre de recherche de votre navigateur.3
