# TP2 — Fiche de surface d'attaque d'ACME

Nom / identifiant : MUSTAFA HE202470
Date :23-10-26
Position d'observation : Kali, hôte des deux réseaux Docker du labo.

## Carte observée

| IP | Ports et protocoles testés | Services / versions identifiées | Limites / vérifications restantes |
|---|---|---|---|
| 172.21.0.10 | 80 tcp|HTTP - Apache httpd 2.4.69 | |
| 172.21.0.11 | 22 tcp|SSH - OpenSSH 8.9|  |
| 172.21.0.13 | 6379 tcp|Redis - 7.4.11| |
| 172.21.0.14 | / | / | |
| 172.21.0.12 | 3306 tcp|MySQL - 8.0.43| |
| 172.21.0.13 | 139 et 445 tcp|SMB - SAMBA smbd 4 | |
| 172.21.0.14 | 161 udp |SNMP - SNMPv1 server| |

Les passerelles `.1` sont des interfaces de Kali : les distinguer des sept cibles.
Une version non identifiée ou une vulnérabilité non démontrée n'est pas à inventer.

## Constat 1

- Observation et preuve (commande, fichier de sortie ou paquet) :
- Condition d'accès (invité, compte fourni, secret partagé, test de vulnérabilité) :
- Risque / information réellement accessible :
- Ce que la preuve ne démontre pas :
- Protection proposée et vérification attendue (y compris l'usage légitime) :

## Constat 2

- Observation et preuve :
- Condition d'accès :
- Risque / information réellement accessible :
- Ce que la preuve ne démontre pas :
- Protection proposée et vérification attendue :

## Synthèse

Que corriger en premier, et pourquoi ? (3 lignes maximum)

## Traces conservées

- Sorties Nmap :
- PCAP et paquet commenté :
- Preuve pour Moodle : capture + commande + une phrase.
