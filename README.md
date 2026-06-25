# 🌐 WDL Overlays & Management-Tools

Willkommen im offiziellen Repository für die **WDL Overlays & Management-Tools** des **World DayLight (WDL)** Teams! Hier findest du alle aktuellen Dateien, die für unseren professionellen Stream-Auftritt plattformübergreifend benötigt werden.

---

## 🚀 Inhalt & Funktionen des Repositories

Dieses Paket enthält alle wichtigen Komponenten für unsere Live-Streams:

*   **`wdl-stream-overlays.zip`** *(Empfohlen)*: Unser maßgeschneidertes Control-Panel zur externen Steuerung der Overlays – sauber verpackt als ZIP-Archiv für einen sicheren und schnellen Download.
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

## 🎨 Verbesserte Erweiterungs-Overlays (Live-Start-v5)
<img width="800" alt="Live-Start-v5" src="https://github.com/user-attachments/assets/62b6e443-476d-412c-81ae-342ed778843f" /> 

---

## 🛠️ Einrichtung & Verwendung (Plattformunabhängig)

Die Overlays basieren auf HTML5/CSS/JS und sind somit mit **jeder modernen Streaming-Software** (z. B. OBS Studio, Streamlabs, vMix, Twitch Studio) kompatibel.

### 1. Control-Panel (WDL Overlays) nutzen
*   Lade dir die `wdl-stream-overlays.zip` herunter und entpacke sie auf deinem PC.
*   Starte die darin enthaltene `.exe`, um das externe Steuerungs-Panel zu öffnen.
*  Die EXE habe ich erstmal hier raus gelöscht weil man das noch nicht komplett fertigt habe.
### 2. Overlays in deiner Streaming-Software einbinden
*   Füge in deiner Streaming-Software eine neue **Browserquelle** (Browser Source) hinzu.
*   Aktiviere die Option für **"Lokale Datei"** (Local file).
*   Klicke auf *Durchsuchen* und wähle die gewünschte HTML-Datei aus.
*   Stelle die Auflösung am besten auf **1920x1080** ein.

### 3. Direkte Steuerung über die Streaming-Software (Ohne Panel)
*   Du musst das Control-Panel nicht zwingend im Hintergrund laufen lassen!
*   Mache in deiner Software einfach einen **Rechtsklick auf die Browserquelle** und wähle die Interaktions-Funktion (in OBS heißt das **"Interagieren" / "Interact"**).
*   Es öffnet sich ein Vorschaufenster, in dem du das Overlay direkt anklicken, bedienen, Hintergründe ändern, Farben auswählen und alles live im Stream bearbeiten kannst.
# 🌐 WDL Overlays // Command Deck

Das offizielle Steuerzentrum für die WDL-Stream-Overlays. Mit diesem Tool hast du die volle Kontrolle über deine Live-Overlays und Streaming-Elemente über eine elegante Cyber-Studio-Schnittstelle.

## 🚀 Installation & Nutzung
Wenn du die fertige Anwendung nutzen möchtest, lade dir die neueste Version unter [Releases](https://github.com/world-Daylight/wdl-stream-overlays/releases) herunter.

## 🛠 Entwicklung (Self-Build)
Wenn du den Code bearbeiten oder das Programm selbst bauen möchtest:

## 🛠 Entwicklung (Self-Build)
Wenn du den Code bearbeiten oder das Programm selbst bauen möchtest:

### 1. 
git clone [https://github.com/world-Daylight/wdl-stream-overlays.git](https://github.com/world-Daylight/wdl-stream-overlays.git)
cd wdl-stream-overlays
### 2. 
*   Abhängigkeiten installieren:
npm install
### 3. 
*   Anwendung im Testmodus starten:
npm start
### 4. 
*   Eigene .exe mit eigenem Icon erstellen:
*   Stelle sicher, dass eine icon.ico im Hauptordner liegt und führe aus:
npm run build

Die fertige Datei findest du im dist/-Ordner. 
---

## 👥 Team & Support
Dieses Projekt wird exklusiv für das **Team: Twitch Live** und die WDL-Community bereitgestellt. Bei Fragen oder technischen Problemen wende dich direkt an den Support im unter wdl-gs.de!

*Design & Development by WDL PavelPascha.*
*Powered by Electron & Tailwind CSS | © WDL PavelPascha*
