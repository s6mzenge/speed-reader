# 📚 Speed Reader - PDF & EPUB

Ein moderner, browserbasierter Speed Reader mit RSVP-Technik (Rapid Serial Visual Presentation) für PDFs und EPUB-Dateien. Keine Installation erforderlich - läuft komplett im Browser!

![Speed Reader](https://img.shields.io/badge/Speed%20Reader-v1.0-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Features

- 📖 **PDF & EPUB Support** - Liest beide gängigen E-Book-Formate
- ⚡ **RSVP-Technik** - Zeigt Wörter einzeln in schneller Folge
- 🎯 **ORP-Highlighting** - Optimaler Erkennungspunkt für schnelleres Lesen
- 🎮 **Vollständige Kontrolle** - Play, Pause, Skip, Reset
- ⌨️ **Tastaturkürzel** - Schnelle Navigation ohne Maus
- 🎨 **Modernes Design** - Ansprechendes, responsives Interface
- 📊 **Statistiken** - Zeigt Fortschritt und verbleibende Zeit
- 🔧 **Anpassbar** - Geschwindigkeit, Schriftgröße und Wortgruppierung

## 🚀 Schnellstart

### Option 1: Lokal ausführen

1. Repository klonen:
```bash
git clone https://github.com/[dein-username]/speed-reader.git
cd speed-reader
```

2. Die `index.html` Datei in einem modernen Browser öffnen:
   - Doppelklick auf die Datei
   - Oder mit einem lokalen Server (z.B. `python -m http.server 8000`)

### Option 2: GitHub Pages

1. Fork dieses Repository
2. Gehe zu Settings → Pages
3. Wähle "Deploy from a branch" → main → / (root)
4. Deine App ist verfügbar unter: `https://[dein-username].github.io/speed-reader/`

## 🎮 Bedienung

### Maus-Steuerung
- **Datei laden**: Klick auf "PDF oder EPUB auswählen" oder Drag & Drop
- **Start/Pause**: Klick auf Play/Pause Button
- **Navigation**: Nutze die Skip-Buttons für ±10 Wörter
- **Geschwindigkeit**: Schieberegler von 100-1000 WPM
- **Wortgruppierung**: 1-5 Wörter gleichzeitig anzeigen
- **Schriftgröße**: Anpassbar von 2em bis 8em

### Tastaturkürzel
- `Leertaste` - Play/Pause
- `←` - 10 Wörter zurück
- `→` - 10 Wörter vor
- `↑` - Geschwindigkeit erhöhen (+50 WPM)
- `↓` - Geschwindigkeit verringern (-50 WPM)

## 🛠️ Technologie

Der Speed Reader nutzt folgende Technologien:

- **PDF.js** - Mozilla's JavaScript PDF-Renderer
- **epub.js** - JavaScript EPUB-Reader
- **Vanilla JavaScript** - Keine Framework-Abhängigkeiten
- **CSS3** - Moderne Animationen und Gradients
- **HTML5** - Drag & Drop API, File API

## 📈 Speed Reading Tipps

### Anfänger (200-300 WPM)
- Starte mit 200-250 WPM
- Nutze 1 Wort pro Anzeige
- Mache regelmäßig Pausen

### Fortgeschrittene (400-600 WPM)
- Erhöhe schrittweise auf 400-500 WPM
- Experimentiere mit 2-3 Wörtern gleichzeitig
- Fokussiere auf den gelben Buchstaben (ORP)

### Experten (700+ WPM)
- 700-1000 WPM möglich
- Nutze Wortgruppen für besseres Verständnis
- Trainiere regelmäßig für beste Ergebnisse

## 🔧 Anpassungen

### Farben ändern
Bearbeite die CSS-Variablen im `<style>` Bereich:
```css
/* Hauptfarben */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Neue Features hinzufügen
- Dark Mode
- Lesezeichen-Funktion
- Export von Notizen
- Mehrsprachige Unterstützung

## 📝 Projektstruktur

```
speed-reader/
│
├── index.html          # Hauptanwendung (All-in-One)
├── README.md          # Diese Datei
└── LICENSE           # MIT Lizenz
```

## 🤝 Beitragen

Contributions sind willkommen! 

1. Fork das Projekt
2. Erstelle einen Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Committe deine Änderungen (`git commit -m 'Add some AmazingFeature'`)
4. Push zum Branch (`git push origin feature/AmazingFeature`)
5. Öffne einen Pull Request

## 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe [LICENSE](LICENSE) für Details.

## 🙏 Danksagungen

- Mozilla PDF.js Team
- Futurepress epub.js Team
- Die Speed Reading Community

## 📮 Kontakt

Bei Fragen oder Feedback, öffne gerne ein [Issue](https://github.com/[dein-username]/speed-reader/issues)!

---

**Happy Speed Reading! ⚡📚**
