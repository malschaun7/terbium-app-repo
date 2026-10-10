# malschaun7 NAS Apps

Terbium-App-Repo für einen separat laufenden Google-Chrome-Container.
Kein offizielles Google- oder Terbium-Projekt. Das Icon ist ein eigenes NAS-Browser-Symbol.

## Repo veröffentlichen

Ein öffentliches GitHub-Repo `malschaun7/terbium-app-repo` mit Branch `main` erstellen.
Den INHALT dieses Ordners ins Repo hochladen: manifest.json, apps.json, README.md, assets und .gitignore.
Keine NAS-Konfiguration, Passwörter oder Browserprofile hochladen.

Terbium v2: Repository-Manifest:
https://raw.githubusercontent.com/malschaun7/terbium-app-repo/main/manifest.json

Ältere Versionen mit apps.json-Format:
https://raw.githubusercontent.com/malschaun7/terbium-app-repo/main/apps.json

Diese URLs funktionieren erst nach dem Hochladen. Wenn Terbium eine Basisadresse statt einer Manifest-Datei verlangt, die Basisadresse https://raw.githubusercontent.com/malschaun7/terbium-app-repo/main/ verwenden.

Die App öffnet https://192.168.178.168:7777/ direkt (proxy: false).
Der Chrome-Container muss separat gestartet sein. Nur im Heimnetz bzw. über einen geeigneten VPN-Zugang erreichbar.
