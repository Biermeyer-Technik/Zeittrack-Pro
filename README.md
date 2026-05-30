# ZeitTrack Pro – Arbeitsstunden App

Eine PWA (Progressive Web App) zur Erfassung von Arbeitsstunden.
Mitarbeiter können die App auf dem Handy installieren und Monatsberichte
direkt per E-Mail an den Steuerberater schicken.

---

## 🚀 Deployment in 5 Schritten

### Schritt 1 – GitHub Account anlegen
→ https://github.com → „Sign up" → kostenlos registrieren

### Schritt 2 – Neues Repository erstellen
1. Auf GitHub: „New repository"
2. Name: `zeittrack-pro`
3. Public auswählen → „Create repository"

### Schritt 3 – Dateien hochladen
1. Klick auf „uploading an existing file"
2. Alle Dateien aus diesem ZIP-Ordner hochladen
3. „Commit changes" klicken

### Schritt 4 – Vercel verbinden (kostenlos)
1. → https://vercel.com → „Sign up with GitHub"
2. „New Project" → dein `zeittrack-pro` Repository auswählen
3. Framework: **Vite** auswählen
4. „Deploy" klicken → fertig in ~2 Minuten!

### Schritt 5 – URL an Mitarbeiter schicken
Vercel gibt dir eine URL wie: `zeittrack-pro.vercel.app`
Diese URL per WhatsApp oder E-Mail an alle Mitarbeiter schicken.

---

## 📱 App auf dem Handy installieren (für Mitarbeiter)

**iPhone (Safari):**
1. URL im Safari öffnen
2. Teilen-Symbol → „Zum Home-Bildschirm"
3. App erscheint wie eine echte App

**Android (Chrome):**
1. URL in Chrome öffnen
2. Drei Punkte → „Zum Startbildschirm hinzufügen"

---

## 🔧 Lokale Entwicklung

```bash
npm install
npm run dev
```

Build für Produktion:
```bash
npm run build
```

---

## 📋 Funktionen

- ✅ Tägliche Erfassung: Beginn, Ende, Pause, Notiz
- ✅ Automatische Stundenberechnung
- ✅ Monatsnavigation
- ✅ Wochenenden automatisch ausgegraut
- ✅ Monatsbericht per E-Mail direkt an Steuerberater
- ✅ Daten bleiben lokal gespeichert (auch offline)
- ✅ Als App auf dem Handy installierbar (PWA)
- ✅ Einstellungen: Name, Position, Steuerberater-E-Mail

---

Erstellt mit ZeitTrack Pro
