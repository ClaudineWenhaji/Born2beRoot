# Born2beRoot
L'objectif de ce projet est de creer sa machine virtuelle

# Machine Virtuelle

Une machine virtuelle (VM) est un ordinateur simulé à l’intérieur d’un autre ordinateur.
Autrement dit : c’est comme si tu avais un deuxième PC qui tourne dans une fenêtre sur ton vrai PC

La VM sert a:

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

# Hardware - Software

On appelle hardware l’ensemble des composants matériels qui constituent un appareil informatique.
Autrement dit, c’est tout ce que l’on peut toucher physiquement dans un ordinateur, un smartphone, une console, etc.

🧩 Exemples de hardware :
* Le processeur (CPU)
* La mémoire vive (RAM)
* Le disque dur ou SSD
* La carte mère
* La carte graphique (GPU)
* L’écran, le clavier, la souris
* Les câbles, ports USB, etc.

Le software (logiciel)
C’est tout ce que tu ne peux pas toucher, c’est-à-dire les programmes et applications.

Exemples :
* Windows, macOS, Linux (systèmes d’exploitation)
* Google Chrome, WhatsApp, Word, Excel
* Jeux vidéo (Fortnite, Minecraft…)
* Applications mobiles
* Pilotes (drivers) qui permettent au hardware de fonctionner

Hardware = matériel
Software = programmes

Les deux sont indispensables :
➡️ Sans software, le hardware ne sait rien faire.
➡️ Sans hardware, le software n’a nulle part pour fonctionner

# Systeme d'exploitation: Debian

Debian est un système d’exploitation Linux, l’une des plus anciennes et les plus utilisées, réputée pour sa stabilité, sa sécurité et son côté libre/open-source.

Debian utilise le gestionnaire de paquet APT pour installer et mettre à jour les logiciels (avec des commandes comme apt install).

# Comment fonctionne une Machine Virtuelle?

Tu utilises un logiciel spécial appelé **hyperviseur**, comme :
* VirtualBox
* VMware
* Hyper-V
*  etc...

L'Hyperviseur crée un environnement virtuel qui imite un vrai ordinateur : processeur, disque dur, RAM, carte réseau, etc.
C'est est un logiciel (ou une couche spécialisée) qui permet de créer et gérer des machines virtuelles

<img width="600" height="306" alt="Virtualization" src="https://github.com/user-attachments/assets/91e9e23c-9ee5-4aa9-b5b5-a59751089e26" />

Il existe deux types d’hyperviseurs :

🟦 Hyperviseur de type 1 (Bare Metal)

Installé directement sur la machine, sans système d’exploitation intermédiaire.

Très performant, utilisé dans les serveurs.

Exemples : VMware ESXi, Microsoft Hyper-V Server, Proxmox

🟩 Hyperviseur de type 2

Fonctionne sur un système d’exploitation (Windows, Linux, macOS).

Parfait pour tester et apprendre.

Exemples : VirtualBox, VMware Workstation, Parallels Desktop

La **VirtualBox** est un logiciel précis qui permet d’utiliser un hyperviseur de type 2.

➡️ C’est une application que tu installes sur ton PC.
➡️ Elle utilise l’hyperviseur pour faire tourner les machines virtuelles.




