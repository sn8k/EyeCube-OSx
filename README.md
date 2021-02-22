# EyeCube-OSx

OSX : Fichiers d'install et de demarrage pour les cartes meres ECM-QM77

Version OSX en test : High Sierra 10.13.6

Statut actuel :

Installation / partition APFS = OK
Boot Mac OS = OK

Materiel :
Intel Graphics HD2500 (celeron 1020e) = semi OK depuis V2 (NO QE/NO CI - graphics glitches & slowdowns)
audio - untested 
Sata - OK (natif)
TRIM - OK (natif)
USB - OK (depuis V2) (USBEnabler)
Reboot - OK
APM - NOK
ETH0 - OK / Fullspeed (IntelMausi)
ETH1 - NOK
WIFI - NOK
BT - NOK

note perso :
- à mettre à jour pour Mojave - serait la derniere version a supporter nativement la hd2500
- mettre a jour clover
- patcher le DSDT si besoin
- convertir en openCore
