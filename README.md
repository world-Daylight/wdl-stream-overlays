# 🌐 WDL Overlays & Management-Tools

Willkommen im offiziellen Repository für die **WDL Overlays & Management-Tools** des **World DayLight (WDL)** Teams! Hier findest du alle aktuellen Dateien, die für unseren professionellen Stream-Auftritt plattformübergreifend benötigt werden.

---


## 🚀 Release / Update: Hotkey & Einzelmodus Unterstützung (`v5`)

Mit diesem Update erhält das Overlay eine flexible Möglichkeit, Benachrichtigungen gezielt per OBS-Hotkey oder Szenenwechsel abzuspielen – ohne dass der automatische Intervall-Wechsler dazwischenfunkt.

---

### ✨ Neue Funktionen

* **`?type=` URL-Parameter:** Du kannst Benachrichtigungen jetzt einzeln über die URL ansteuern.
* **Automatischer Einzelmodus:** Sobald ein `?type=` im Link erkannt wird, deaktiviert sich das zeitgesteuerte Intervall automatisch. Die Benachrichtigung wird einmalig beim Einblenden/Laden abgespielt.
* **Hotkey-Steuerung via OBS:** Perfekt für die Einbindung als Browserquelle, die per Tastendruck oder Stream Deck eingeblendet wird.

---

### 🔗 URL-Parameter Übersicht

Füge deiner Browserquelle in OBS einfach den passenden Parameter an das Ende des Dateinamens an:

| Benachrichtigung | URL-Aufruf | Alternative (Index) |
| :--- | :--- | :--- |
| **👍 Like / Daumen hoch** | `notification-v5.html?type=like` | `notification-v5.html?type=0` |
| **🔔 Abonnement** | `notification-v5.html?type=abo` | `notification-v5.html?type=1` |
| **💬 Kommentare** | `notification-v5.html?type=comment` | `notification-v5.html?type=2` |

> 💡 **Hinweis:** Ohne den Parameter `?type=` verhält sich das Overlay wie gewohnt und wechselt alle 3 Benachrichtigungen automatisch im eingestellten Zeitintervall durch.

---

### 🛠️ Anleitung: Einbindung per OBS-Hotkey

1. Legen Sie eine neue **Browserquelle** in OBS Studio an und wählen Sie die lokale Datei `notification-v5.html` aus.
2. Ergänzen Sie im Pfad/URL den gewünschten Typen (z. B. `notification-v5.html?type=like`).
3. Öffnen Sie in OBS die **Einstellungen** ➔ **Hotkeys**.
4. Suchen Sie nach der neu erstellten Browserquelle und belegen Sie das Feld **"Einblenden"** *(Show)* mit einer beliebigen Taste oder einem Stream-Deck-Button.
5. **Fertig!** Bei Betätigen des Hotkeys blendet OBS die Quelle ein, die Animation spielt ab und das Overlay blendet sich nach Ablauf der eingestellten Anzeigedauer selbstständig wieder aus.




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

Die Overlays basieren auf standardisierten Web-Technologien (HTML5, CSS & JS) und lassen sich daher in allen gängigen Streaming- und Aufnahmeprogrammen problemlos einbinden, die Browser-Quellen unterstützen (z. B. OBS Studio, Streamlabs, vMix oder Twitch Studio).

### 1. Control-Panel (WDL Overlays) nutzen
*   Lade dir die `wdl-stream-overlays.zip` herunter und entpacke sie auf deinem PC.
*   Starte die darin enthaltene `.exe`, um das externe Steuerungs-Panel zu öffnen.
*   *Hinweis: Die `.exe`-Datei wurde vorübergehend aus dem Repository entfernt, da sich das Panel noch in der aktiven Entwicklung befindet.*
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
