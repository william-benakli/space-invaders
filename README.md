# Space Invaders

Ce projet est basé sur le jeu **Space Invaders** qu’on peut bien sûr essayer gratuitement sur nos smartphone ou sur le **Web**.
Le but de ce projet qui comptera dans la note finale de la matière Projet C, est de reproduire le jeu **Space Invaders**, sans en faire une copie parfaite du jeu original, mais de le reproduire à notre façon en fonction de notre niveau en programmation dans le langage de programmation **C**.

[![forthebadge](data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNDcuNTQwMDAwMDAwMDAwMDIiIGhlaWdodD0iMzUiIHZpZXdCb3g9IjAgMCAxNDcuNTQwMDAwMDAwMDAwMDIgMzUiPjxyZWN0IGNsYXNzPSJzdmdfX3JlY3QiIHg9IjAiIHk9IjAiIHdpZHRoPSIxMTUuMzEiIGhlaWdodD0iMzUiIGZpbGw9IiNDMTNCM0EiLz48cmVjdCBjbGFzcz0ic3ZnX19yZWN0IiB4PSIxMTMuMzEiIHk9IjAiIHdpZHRoPSIzNC4yMzAwMDAwMDAwMDAwMiIgaGVpZ2h0PSIzNSIgZmlsbD0iI0U0NkMxNyIvPjxwYXRoIGNsYXNzPSJzdmdfX3RleHQiIGQ9Ik0xNS42OSAyMkwxNC4yMiAyMkwxNC4yMiAxMy40N0wxNi4xNCAxMy40N0wxOC42MCAyMC4wMUwyMS4wNiAxMy40N0wyMi45NyAxMy40N0wyMi45NyAyMkwyMS40OSAyMkwyMS40OSAxOS4xOUwyMS42NCAxNS40M0wxOS4xMiAyMkwxOC4wNiAyMkwxNS41NSAxNS40M0wxNS42OSAxOS4xOUwxNS42OSAyMlpNMjguNDkgMjJMMjYuOTUgMjJMMzAuMTcgMTMuNDdMMzEuNTAgMTMuNDdMMzQuNzMgMjJMMzMuMTggMjJMMzIuNDkgMjAuMDFMMjkuMTggMjAuMDFMMjguNDkgMjJaTTMwLjgzIDE1LjI4TDI5LjYwIDE4LjgyTDMyLjA3IDE4LjgyTDMwLjgzIDE1LjI4Wk00MS4xNCAyMkwzOC42OSAyMkwzOC42OSAxMy40N0w0MS4yMSAxMy40N1E0Mi4zNCAxMy40NyA0My4yMSAxMy45N1E0NC4wOSAxNC40OCA0NC41NyAxNS40MFE0NS4wNSAxNi4zMyA0NS4wNSAxNy41Mkw0NS4wNSAxNy41Mkw0NS4wNSAxNy45NVE0NS4wNSAxOS4xNiA0NC41NyAyMC4wOFE0NC4wOCAyMS4wMCA0My4xOSAyMS41MFE0Mi4zMCAyMiA0MS4xNCAyMkw0MS4xNCAyMlpNNDAuMTcgMTQuNjZMNDAuMTcgMjAuODJMNDEuMTQgMjAuODJRNDIuMzAgMjAuODIgNDIuOTMgMjAuMDlRNDMuNTUgMTkuMzYgNDMuNTYgMTcuOTlMNDMuNTYgMTcuOTlMNDMuNTYgMTcuNTJRNDMuNTYgMTYuMTMgNDIuOTYgMTUuNDBRNDIuMzUgMTQuNjYgNDEuMjEgMTQuNjZMNDEuMjEgMTQuNjZMNDAuMTcgMTQuNjZaTTU1LjA5IDIyTDQ5LjUxIDIyTDQ5LjUxIDEzLjQ3TDU1LjA1IDEzLjQ3TDU1LjA1IDE0LjY2TDUxLjAwIDE0LjY2TDUxLjAwIDE3LjAyTDU0LjUwIDE3LjAyTDU0LjUwIDE4LjE5TDUxLjAwIDE4LjE5TDUxLjAwIDIwLjgyTDU1LjA5IDIwLjgyTDU1LjA5IDIyWk02Ni42NSAyMkw2NC42OCAxMy40N0w2Ni4xNSAxMy40N0w2Ny40NyAxOS44OEw2OS4xMCAxMy40N0w3MC4zNCAxMy40N0w3MS45NiAxOS44OUw3My4yNyAxMy40N0w3NC43NCAxMy40N0w3Mi43NyAyMkw3MS4zNSAyMkw2OS43MyAxNS43N0w2OC4wNyAyMkw2Ni42NSAyMlpNODAuMzggMjJMNzguOTAgMjJMNzguOTAgMTMuNDdMODAuMzggMTMuNDdMODAuMzggMjJaTTg2Ljg3IDE0LjY2TDg0LjIzIDE0LjY2TDg0LjIzIDEzLjQ3TDkxLjAwIDEzLjQ3TDkxLjAwIDE0LjY2TDg4LjM0IDE0LjY2TDg4LjM0IDIyTDg2Ljg3IDIyTDg2Ljg3IDE0LjY2Wk05Ni4yNCAyMkw5NC43NSAyMkw5NC43NSAxMy40N0w5Ni4yNCAxMy40N0w5Ni4yNCAxNy4wMkwxMDAuMDUgMTcuMDJMMTAwLjA1IDEzLjQ3TDEwMS41MyAxMy40N0wxMDEuNTMgMjJMMTAwLjA1IDIyTDEwMC4wNSAxOC4yMUw5Ni4yNCAxOC4yMUw5Ni4yNCAyMloiIGZpbGw9IiNGRkZGRkYiLz48cGF0aCBjbGFzcz0ic3ZnX190ZXh0IiBkPSJNMTI3LjA3IDE3LjgwTDEyNy4wNyAxNy44MFExMjcuMDcgMTYuNTQgMTI3LjY3IDE1LjU0UTEyOC4yNyAxNC41NSAxMjkuMzIgMTMuOTlRMTMwLjM3IDEzLjQzIDEzMS42OSAxMy40M0wxMzEuNjkgMTMuNDNRMTMyLjg0IDEzLjQzIDEzMy43NiAxMy44NFExMzQuNjkgMTQuMjUgMTM1LjMwIDE1LjAyTDEzNS4zMCAxNS4wMkwxMzMuNzkgMTYuMzlRMTMyLjk4IDE1LjQwIDEzMS44MSAxNS40MEwxMzEuODEgMTUuNDBRMTMxLjEyIDE1LjQwIDEzMC41OSAxNS43MFExMzAuMDYgMTYgMTI5Ljc2IDE2LjU0UTEyOS40NyAxNy4wOSAxMjkuNDcgMTcuODBMMTI5LjQ3IDE3LjgwUTEyOS40NyAxOC41MSAxMjkuNzYgMTkuMDVRMTMwLjA2IDE5LjYwIDEzMC41OSAxOS45MFExMzEuMTIgMjAuMjAgMTMxLjgxIDIwLjIwTDEzMS44MSAyMC4yMFExMzIuOTggMjAuMjAgMTMzLjc5IDE5LjIyTDEzMy43OSAxOS4yMkwxMzUuMzAgMjAuNThRMTM0LjY5IDIxLjM1IDEzMy43NyAyMS43NlExMzIuODQgMjIuMTcgMTMxLjY5IDIyLjE3TDEzMS42OSAyMi4xN1ExMzAuMzcgMjIuMTcgMTI5LjMyIDIxLjYxUTEyOC4yNyAyMS4wNSAxMjcuNjcgMjAuMDVRMTI3LjA3IDE5LjA2IDEyNy4wNyAxNy44MFoiIGZpbGw9IiNGRkZGRkYiIHg9IjEyNi4zMSIvPjwvc3ZnPg==)](https://forthebadge.com)

## Pour commencer

Une fois le projet lancé, bien lire et faire ce qu'il est demandé par rapport a ce que vous voulez faire.

### Pré-requis

- **JAVA** d'installer sur sa machine

## Démarrage

Double-click sur le fichier "**Launcher.bat**" et le projet sera lancé.

**Si** le projet ne ce lance pas ou que le fichier "**Launcher.bat**" n'existe pas alors :

 * Placez vous dans le dossier source, copier le chemin.
 * Ouvrez votre terminal de commande, rentrer ceci : *cd "coller le chemin que vous avez copier auparavant"*
 * Puis rentrer pour compiler le projet : *javac "le chemin vers le fichier **Test.java** contenant le main"*
 * Et enfin pour le lancer, rentrer : *java "le chemin vers le fichier **Test** sans un .java ou un .class derriere celui ci"

## Fabriqué avec

* [Intellij IDEA](https://www.jetbrains.com/fr-fr/idea/) - IDE 
* [Eclipse](https://www.eclipse.org/) - IDE
* [JAVA](https://www.java.com/fr/) - Langage de programmation
* [JAVA.AWT](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html) - Interface Graphique
* [JAVA.UTIL.SCANNER](https://docs.oracle.com/javase/7/docs/api/java/util/Scanner.html) - Interaction avec l'utilisateur
* [JAVA.IO.Serializable](https://docs.oracle.com/javase/7/docs/api/java/io/Serializable.html) - Sauvegarde en Files
* [JAVA.NIO.FILE](https://docs.oracle.com/javase/7/docs/api/java/nio/file/Files.html) - Utilisation des Files

## Auteurs

* **NZABA Eric**
* **PHAM Hoang-Lân**


