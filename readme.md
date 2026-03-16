# 🦅 Hawks Toolbox v2.7.2

> **All-in-One Admin Suite für die Zimmerberg Hawks.**
> Planen, Gestalten, Verwalten und Turniere organisieren – alles in einer App.

![Version](https://img.shields.io/badge/version-2.7.2-indigo?style=for-the-badge)
![Tech](https://img.shields.io/badge/Electron-React-blue?style=for-the-badge&logo=react)
![Style](https://img.shields.io/badge/Tailwind-CSS-38bdf8?style=for-the-badge&logo=tailwindcss)

## 🌟 Übersicht

Die **Hawks Toolbox** ist eine leistungsstarke Desktop-Anwendung, die verschiedene administrative Aufgaben für Trainer und Vereinsfunktionäre bündelt. Sie vereint moderne React-Module mit bewährten Tools in einer einheitlichen Oberfläche.

---

## 🚀 Die Module

### 1. 📋 Team Manager
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

### 3. 🎨 Social Media Generator
Das Grafik-Monster für Match-Ankündigungen und Resultate.
* **API-Anbindung:** Lädt Spiele direkt von Swiss Unihockey.
* **Design-Kontrolle:** Volle Kontrolle über Schriftarten, Grössen und Abstände.
* **Modi:** Umschaltbar zwischen "Vorschau" (Next Games) und "Resultate".

### 4. 💰 Cloud Budget
Finanzplanung leicht gemacht.
* **Planung:** Einnahmen und Ausgaben erfassen.
* **Übersicht:** Automatische Berechnung von Totals und Saldo.
* **Print:** Sauberer Ausdruck für Sitzungen.

### 5. 🗺️ Hallenplaner
Das Tool für die Infrastruktur.
* **Planung:** Hallenbelegung planen.
* **Übersicht:** Einfaches visuelles Tool zur Ressourcen-Einteilung.

### 6. 📱 Aufgebots-Generator
Das Kommandozentrum für den Matchday.
* **Smart Import:** Lädt Kader direkt aus dem Team Manager.
* **Lineup & Blöcke:** Taktische Einteilung für Kleinfeld (3er) und Grossfeld (5er) inklusive Special Teams (Power Play / Boxplay).
* **Auto-Tetris:** Fahrer und freie Plätze für Auswärtsspiele verwalten.
* **WhatsApp & PDF Export:** Mit einem Klick das perfekt formatierte Aufgebot in den Team-Chat posten oder als sauberes Dokument ausdrucken.

### 7. ⏱️ Live Scoreboard (NEU)
Das ultimative Kommandozentrum für den Jury-Tisch am Matchday.
* **Dual-Screen Magie:** Laptop als Controller nutzen und das Scoreboard auf einem zweiten Monitor oder Beamer für die Zuschauer im Vollbild anzeigen (Echtzeit-Sync).
* **Match-Uhr & Auto-Horn:** Vorwärts oder rückwärts laufende Zeit, schnelle Korrektur-Buttons (Sekunden/Minuten) und ein integriertes Hallen-Horn.
* **Smarte Strafen-Matrix:** Automatische Warteschlange für Kleinfeld (max. 1 laufende Strafe) und Grossfeld (max. 2). Unterstützt 2', 2+2' und 10' Strafen inklusive nachträglicher Eingabe der Trikotnummer.
* **Timeouts:** Ein-Klick-Timeout pro Team mit 30-Sekunden-Countdown direkt auf dem grossen Display.

---

## ⚡ Installation & Entwicklung

Voraussetzung: [Node.js](https://nodejs.org/) installiert.

### Entwicklung starten
```bash
# Abhängigkeiten installieren
npm install

# App im Dev-Modus starten (Hot Reload)
npm run dev

---

© 2026 Zimmerberg Hawks | Built by Steven


