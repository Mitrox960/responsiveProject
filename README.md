# responsiveProject
SN2 Projet responsive
Groupe : Dorian Groner, Damien Loubiou, Mateo Lo Pinto

Pages HTML dans dossier Template à la racine du projet
Ouvrir sur un serveur la page Blank


Conception des pages pour naviguer :
Comme montrer sur le site, il est alors possible de mettre une sidebare commune aux pages webs permettant un accès plus simple et optimale au client. Mais alors comment?
Il est important d'importer le code de la sidebar dans un autre fichier, le fichier ayant été nommé sidebar.html dans notre projet.
Une fois le code mis, il va falloir retourner sur la page, laquelle où on veut ajouter celle sidebare, puis rajouter une include au niveau de la ligne où nous souhaitons l'ajouts.
Une fois cela fait, il est important d'écrire un script java juste avant de fermé le body indiquant qu'il y a eu un include, et comment il doit procéder pour importer un code HTML d'une page à une autre.