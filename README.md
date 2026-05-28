# 🌐 WDL Stream Overlays & Tools

Willkommen im offiziellen Repository für die Stream-Overlays und Management-Tools des **World DayLight (WDL)** Teams! Hier findest du alle aktuellen Dateien, die für unseren professionellen Stream-Auftritt plattformübergreifend benötigt werden.

---

## 🚀 Inhalt & Funktionen des Repositories

Dieses Paket enthält alle wichtigen Komponenten für unsere Live-Streams:

*   **`wdl-stream-overlays.exe`**: Unser maßgeschneidertes Control-Panel zur externen Steuerung der Overlays.
*   **HTML-Overlays**: 
    *   `Overlays-start.html` – Das Haupt-Steuerungscenter. Hier hast du maximale Flexibilität: Du kannst direkt eigene Hintergründe hochladen, vordefinierte Hintergründe wählen oder individuelle Farben einstellen.
    *   `Live-Start.html` – Der Start-Screen für den Stream.
    *   `notification.html` – Das Alerts- und Benachrichtigungssystem.
    *   `loeschen.html` – Steuerungs-Interface zum Zurücksetzen oder Leeren von Anzeigen.
    *   `Overlays-start.png` / `.jpg` – Grafische Vorlagen und Design-Inhalte.
*   **Sounds (`.mp3`)**:
    *   `ABONNIEREN-v4.mp3` – Sound-Effekt für neue Abonnenten.
    *   `daumen-hoch.mp3` – Sound-Effekt für Likes/Follows.
    *   `KOMMENTARE.mp3` – Sound-Effekt bei neuen Chat-Interaktionen.

---

## 🛠️ Einrichtung & Verwendung (Plattformunabhängig)

Die Overlays basieren auf HTML5/CSS/JS und sind somit mit **jeder modernen Streaming-Software** (z. B. OBS Studio, Streamlabs, vMix, Twitch Studio) kompatibel.

### 1. Overlays in deiner Streaming-Software einbinden
*   Füge in deiner Streaming-Software eine neue **Browserquelle** (Browser Source / Webpage-Quelle) hinzu.
*   Aktiviere die Option für **"Lokale Datei"** (Local file).
*   Klicke auf *Durchsuchen* und wähle die gewünschte HTML-Datei aus (z. B. `Overlays-start.html`, `Live-Start.html` oder `notification.html`).
*   Stelle die Auflösung in den Eigenschaften der Quelle am besten auf **1920x1080** ein.

### 2. Direkte Steuerung über die Streaming-Software (Ohne `.exe`)
*   Du musst die `.exe` nicht zwingend im Hintergrund laufen lassen!
*   Mache in deiner Software einfach einen **Rechtsklick auf die Browserquelle** und wähle die Interaktions-Funktion (in OBS heißt das **"Interagieren" / "Interact"**).
*   Es öffnet sich ein Vorschaufenster, in dem du das Overlay direkt anklicken, bedienen, Hintergründe ändern, Farben auswählen und alles live im Stream bearbeiten kannst.

---

## 👥 Team & Support
Dieses Projekt wird exklusiv für das **Team: Twitch Live** und die WDL-Community bereitgestellt. Bei Fragen oder technischen Problemen wende dich direkt an den Support im TS3 oder wdl-gs.de!

*Design & Development by WDL PavelPascha.*
