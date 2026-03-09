# TP 1 – Programmation Dynamique par Réflexion
##  Description :
#### Ce projet est une application Java qui démontre l'utilisation de la réflexion  pour charger dynamiquement des classes et injecter des dépendances à partir d’un fichier de configuration.L’application utilise une architecture simple basée sur des interfaces et leurs implémentations pour effectuer un calcul.
## Objectif :
#### - Comprendre le principe de la programmation dynamique en Java.
#### - Utiliser la réflexion pour instancier des classes dynamiquement.
#### - Mettre en pratique le concept d’injection de dépendances.
#### - Charger la configuration d’une application depuis un fichier externe.
## Structure du projet :

![WhatsApp Image 2026-03-09 at 22 21 46](https://github.com/user-attachments/assets/fb9d995b-36d5-470e-bd72-834426ca1ab7)

## Explication :
#### - IDao : interface qui fournit une valeur.
#### - DaoImpl : implémentation qui retourne une valeur fixe.
#### - IMetier : interface contenant la méthode de calcul.
#### - MetierImpl : utilise la DAO pour effectuer un calcul.
#### - Presentation2 : charge les classes dynamiquement à partir du fichier config.txt et injecte la dépendance avec la réflexion.
## Execution :

![WhatsApp Image 2026-03-09 at 22 13 09](https://github.com/user-attachments/assets/f564fb04-2c35-4ac0-8ac5-1bc518b5a8ea)

## Conclusion :
#### Ce TP permet de comprendre comment la réflexion en Java peut être utilisée pour rendre une application plus flexible et modulaire, en séparant la configuration du code source et en facilitant l'injection de dépendances.
