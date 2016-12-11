* [English version](README.md)

# cidr2ip
Petit script pour convertir la notation CIDR en adresses IP distinctes.

## À propos
Étant donné que le dépôt original a disparu, et comme la licence le permet, je republic ce script Perl.

* Auteur original : [Steve Kemp](https://steve.fi/)
* Licence : Comme mentionné dans le script, il utilise la même que Perl (GPLv1 si je suis le README de Perl 5.24). Fait intéressant, le script contient à la fois une mention Copyright ET Logiciel Libre.

## Utilisation
C'est aussi simple que d'appeler le script avec la plage CIDR comme paramètre :
```bash
[seboss666@seboss666-pc ~ ]$ cidr2ip 192.168.1.0/24
192.168.1.0
192.168.1.1
192.168.1.2
192.168.1.3
192.168.1.4
192.168.1.5
(...)
```

## Installation
Téléchargez simplement le script ou clonez ce dépôt, et assurez-vous de l'enregistrer quelque part dans votre variable d'environnement `PATH`. Évidemment, il faut Perl d'installé.

## Limitations connues
Il n'est utilisable que pour les adresses IPv4. Vous devez également utiliser un pipe shell et grep/less/n'importe pour rechercher parmi les résultats.

