# BigProjekt1

## Einführung
BigProjekt1 ist eine Webanwendung, die Nutzern ermöglicht, Aufgaben zu verwalten und zu priorisieren. Mit einer intuitiven Benutzeroberfläche und Echtzeit-Synchronisation bietet BigProjekt1 eine effiziente Möglichkeit, persönliche und berufliche Aufgaben zu organisieren.

## Deployment Anleitung

### Installation und Start

1. Klone das Repository:
   ```sh
   git clone https://github.com/ErikRichter120198/bigprojekt1.git
   cd bigprojekt1
Installiere die Abhängigkeiten:

npm install
Starte die Anwendung:

npm start

Lokale Entwicklung
Stelle sicher, dass Node.js und npm installiert sind.
Führe die oben genannten Schritte aus.


Deployment auf AWS
Erstelle eine EC2-Instanz.
SSH in die Instanz:

ssh -i "dein-schlüssel.pem" ubuntu@ec2-xxx-xxx-xxx-xxx.compute.amazonaws.com

Installiere Node.js und npm:

sudo apt update
sudo apt install nodejs npm

Klone das Repository und installiere die Abhängigkeiten:
git clone https://github.com/ErikRichter120198/bigprojekt1.git
cd bigprojekt1
npm install


Starte die Anwendung:
npm start

## Techstack
- Node.js
- Express
- MongoDB
- React

## Lizenzierung
Dieses Projekt steht unter der MIT-Lizenz. Weitere Informationen findest du in der [LICENSE](./LICENSE)-Datei.
