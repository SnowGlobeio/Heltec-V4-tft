# Heltec-V4-tft
Meshtastic firmware

Dernière version 2.7.18 du 23/01/2026

## Procédure de mise à jour

1) Utliser un navigatreur web de type Chrome, Edge, Brave ...

2) Se rendre sur le site : https://www.espboards.dev/tools/program/ 
   (Il y en a d'autre, mais celui-ci fonctionne très bien)

3) Passer votre Heltec-V4-TFT en mode DFU : 
 - Appuyer sur les boutons <b>"RST"</b> et <b>"USER"</b>
 - Relacher <b>"RST"</b> en gardant le doigt sur <b>"USER"</b>
 - Ralacher <b>"USER"</b> après 2 secondes

4) Connecter le module en USB sur votre pc

5) Régler la vitesse sur <b>"115200"</b> et cliquer sur <b>"Connect"</b> dans l'interface web du site.

6) Cliquer sur <b>"Program"</b>

7) Dans la fenêtre qui s'affiche:
  - indiquer la valeur <b>"0x0"</b> à la place de celle indiquée.
  - Sélectionner le firmware à implanter
  - Cliquer sur <b>"Program"</b> dans la fenêtre.
Une barre de progression vous indique le chargement du firmaware et un message final vous indique que tout s'est bien passé.

8) Une fois la programmation terminée, appuyer sur le bouton <b>"RST"</b> du module pour le rebooter.

   Et voilà !!!
