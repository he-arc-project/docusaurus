---
sidebar_label: 'OS'
sidebar_position: 1
---

# OS

## Windows:
Les noyaux :
- MSDOS: ancien noyau cmd seulement
- (actif) NT: noyau plus récent
- CE: version sys embarqué leger
- Mobile: version telephone

## Linux:
Solution a la privatisation unix (à partir de version 8) avec une nouvelle license gnu gpl

## Interface utilisateur

Fenetre

CMD, powershell, 

batch

## Noyau (kernel)
- execution de programme
    - programme (fichier)
    - processus (entité actif)
        - besoin de ressource pour accomplir sa tache
- composants - entré sortie
    - une entré / sortie est l'interface avec un peripherique
        - clavier souris
        - carte résaux, graphique
    - L'OS est responsable de:
        - Fournir des péripherique generaux
        - Fournir une interface aux driver specifique
        - gèrer la memoir des entrées sorties
- File systems
    - Supports de un ou ou plusieurs sys de fichier
        - EXT4, FAT, NTFS
    - Os est responsable de:
        - CRUD fichier
        - Definir des droits
- Communication
    - Echange d'informations entre processus
    - communication et synchronisation
- Allocation de ressource
    - La memoire est un grand vecteur composé d'octet
    - chaque memoire possede son adresse
    - Volatile: données perdu au demarrage
    - Le CPU met les données de la RAM en CACHE L1 L2 L3 (L1 > L2 > L3, plus petit mais plus rapide)
    - Quand RAM saturé, met les prochaine données dans la SWAP (petite partue du HDD) preventif contres les blue screen et les messages de type overflow si trop d'app lancé