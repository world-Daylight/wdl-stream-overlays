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