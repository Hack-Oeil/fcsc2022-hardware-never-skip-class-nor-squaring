# FCSC 2022 Never Skip Class Nor Squaring

Nous avons accès à un serveur qui permet de signer des messages avec RSA. Lors de la connexion, ce serveur nous transmet un message chiffré que nous voulons déchiffrer.

Le serveur est compromis et il est possible d’injecter des glitchs pour sauter les opérations **de mise au carré** dans l’algorithme square and multiply utilisé pour réaliser l’exponentiation modulaire du RSA.

Retrouvez la clé de déchiffrement et récupérez le message.

Note : Une épreuve similaire est disponible ici : **Never Skip Class Nor Multiplication**.


Fichier :
- [nscns.py](nscns.py)



Auteurs : Ker

Origine : [Never Skip Class Nor Squaring](https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-never-skip-class-nor-squaring/)

-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc never-skip-class-nor-squaring.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-hardware-never-skip-class-nor-squaring.git

> cd fcsc2022-hardware-never-skip-class-nor-squaring


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-never-skip-class-nor-squaring/