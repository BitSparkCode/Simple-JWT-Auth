# JWT Auth Example

Ein einfaches Beispiel für JWT-Authentifizierung mit Node.js und Express, einschliesslich statischer HTML-Seiten und Tailwind CSS.

## Installation

1. Node.js und npm installieren, falls noch nicht geschehen.
2. Repository klonen oder Dateien herunterladen.
3. Abhängigkeiten installieren:
    ```bash
    npm install express jsonwebtoken body-parser
    ```

## Dateien und Verzeichnisse

- `server.js`: Der Haupt-Servercode.
- `public/`: Verzeichnis für statische Dateien.
    - `index.html`: Startseite.
    - `login.html`: Login-Seite.
    - `protected.html`: Geschützte Seite.

## Verwendung

1. Server starten:
    ```bash
    node server.js
    ```

2. Im Browser öffnen:
    - Index-Seite: `http://localhost:3000`
    - Login-Seite: `http://localhost:3000/login` 