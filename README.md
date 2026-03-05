# 🦅 Hawks Toolbox v2.3.2

> **All-in-One Admin Suite für die Zimmerberg Hawks.**
> Planen, Gestalten, Verwalten und Turniere organisieren – alles in einer App.

![Version](https://img.shields.io/badge/version-2.3.2-indigo?style=for-the-badge)
![Tech](https://img.shields.io/badge/Electron-React-blue?style=for-the-badge&logo=react)
![Style](https://img.shields.io/badge/Tailwind-CSS-38bdf8?style=for-the-badge&logo=tailwindcss)

## 🌟 Übersicht

Die **Hawks Toolbox** ist eine leistungsstarke Desktop-Anwendung, die verschiedene administrative Aufgaben für Trainer und Vereinsfunktionäre bündelt. Sie vereint moderne React-Module mit bewährten Tools in einer einheitlichen Oberfläche.

---

## 🚀 Die Module

### 1. 📋 Team Manager (Ultimate Edition)
Das Herzstück für die Saisonplanung.
* **Drag & Drop:** Spieler einfach in Mannschaften ziehen.
* **Smart Import:** CSV-Import mit automatischer Duplikaterkennung.
* **Spieler-Details:** Erfassung von Jahrgang, Bemerkungen und Geschlecht (♂/♀ Icons).
* **Team-Verwaltung:** Trainer, Trainingszeiten und Team-Farben konfigurieren.

### 2. 🏆 Turnier Manager
Ein komplettes Tool zur Durchführung von Turnieren.
* **Spielplan-Generator:** Erstellt automatisch "Jeder gegen Jeden" (Round Robin) Pläne.
* **Zeit-Management:** Automatische Berechnung der Anspielzeiten inkl. Pausen. Ändert sich eine Zeit, passen sich alle nachfolgenden Spiele automatisch an.
* **Live Tabelle:** Berechnet Punkte, Tordifferenz und Rangliste in Echtzeit.
* **Print Mode:** Optimiertes Layout für den Ausdruck (Schwarz/Weiss, ohne UI-Elemente).

### 3. 🎨 Social Media Generator (V90 Engine)
Das Grafik-Monster für Match-Ankündigungen und Resultate.
* **API-Anbindung:** Lädt Spiele direkt von Swiss Unihockey.
* **Design-Kontrolle:** Volle Kontrolle über Schriftarten, Grössen und Abstände.
* **Modi:** Umschaltbar zwischen "Vorschau" (Next Games) und "Resultate".

### 4. 💰 Cloud Budget
Finanzplanung leicht gemacht.
* **Planung:** Einnahmen und Ausgaben erfassen.
* **Übersicht:** Automatische Berechnung von Totals und Saldo.
* **Print:** Sauberer Ausdruck für Sitzungen.

### 5. 🗺️ Hallenplaner (NEU)
Das Tool für die Infrastruktur.
* **Planung:** Hallenbelegung planen.
* **Übersicht:** Einfaches visuelles Tool zur Ressourcen-Einteilung.

---

## ⚡ Installation & Entwicklung

Voraussetzung: [Node.js](https://nodejs.org/) installiert.

### Entwicklung starten
```bash
# Abhängigkeiten installieren
npm install

# App im Dev-Modus starten (Hot Reload)
npm run dev
Exe-Datei bauen (Windows)
Erstellt einen Installer für Windows im Ordner dist.

Bash
npm run dist
💾 Daten & Backup
Die App speichert alle Daten lokal auf dem Gerät (LocalStorage). Es gibt keine Cloud-Datenbank.

WICHTIG für Updates & Umzüge:
Da die Daten lokal liegen, muss vor einem PC-Wechsel oder einer Neuinstallation ein Backup gemacht werden.

Gehe im Team Manager auf Konfiguration ⚙️.

Wähle den Tab IMPORT / BACKUP.

Klicke auf "Backup erstellen (.json)".

Diese Datei kann auf jedem anderen PC wieder importiert werden.

Hinweis: Der Turnier Manager speichert den aktuellen Turnierstand ebenfalls im lokalen Speicher, ist aber (noch) nicht im globalen Backup-File enthalten.

🛠 Tech Stack
Core: Electron (Chromium Container)

Frontend: React + Vite

Styling: Tailwind CSS

Icons: Lucide React

Drag & Drop: @dnd-kit

📂 Projektstruktur
Plaintext
hawks-toolbox/
├── dist/                  # Fertige .exe Dateien (nach Build)
├── public/                # Statische Assets (Bilder, Legacy Tools)
│   ├── tools/             # HTML-Tools (Generator, Budget, Hallenplaner)
│   ├── assets/            # Hintergründe & Logos
│   └── logo.png           # App Icon
├── src/
│   ├── apps/              # Die React Module
│   │   ├── TeamManager.jsx
│   │   ├── TournamentManager.jsx
│   │   └── ...
│   ├── App.jsx            # Hauptmenü & Routing
│   └── main.jsx           # Entry Point
└── package.json           # Config & Scripts
© 2026 Zimmerberg Hawks | Built by Steven
