# EyeCube-OSx

OSX : Fichiers d'install et de demarrage pour les cartes meres ECM-QM77

Version OSX en test : High Sierra 

Statut actuel :

Installation / partition APFS = OK
Boot Mac OS = OK

Materiel :
Intel Graphics HD2500 (celeron 1020e) = semi OK (NO QE/NO CI - graphics glitches & slowdowns)
audio - untested
Sata - OK
TRIM - OK
USB - OK
Reboot - OK
APM - NOK
ETH0 - OK / Fullspeed
ETH1 - NOK

note perso :
- à mettre à jour pour Mojave - serait la derniere version a supporter nativement la hd2500
- mettre a jour clover
- patcher le DSDT si besoin
- convertir en openCore
