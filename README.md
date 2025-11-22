# Born2beRoot
Creer sa machine virtuelle

Une machine virtuelle (VM) est un ordinateur simulé à l’intérieur d’un autre ordinateur.
Autrement dit : c’est comme si tu avais un deuxième PC qui tourne dans une fenêtre sur ton vrai PC

Comment ça fonctionne ?

Tu utilises un logiciel spécial appelé hyperviseur, comme :
* VirtualBox * VMware * Hyper-V * etc...

Ce logiciel crée un environnement virtuel qui imite un vrai ordinateur : processeur, disque dur, RAM, carte réseau, etc.

Elle sert a:

* Tester un système d’exploitation
Ex. : installer Debian, Windows, Ubuntu, etc. sans toucher à ton PC principal
* Faire des tests sans risque
Si tu fais une erreur, tu peux simplement supprimer ou restaurer la machine virtuelle
* Avoir plusieurs systèmes en même temps
Par exemple :
- ton PC Windows → système principal
- une VM Linux → pour développer, apprendre ou expérimente
* Sécurité
Les VM sont isolées du système principal, donc les virus ou erreurs dans la VM ne touchent pas ton vrai PC (en général).
