<p align="center">
  <img src="icon.png" width="120" alt="Stillfeed">
</p>

# Stillfeed

**Reddit, X, Facebook und Instagram – in einer App, nur zum Lesen.**
*Enjoy the (fast) silence.*

Stillfeed bündelt vier soziale Netzwerke in einer ruhigen App zum Lesen.
Werbung, Vorschlagsbeiträge und Reels werden ausgeblendet, Posten,
Kommentieren und Reaktionen sind bewusst nicht möglich. Nur der
Facebook-Messenger bleibt zum Schreiben mit privaten Kontakten offen.

> Dies ist die öffentliche Download- und Feedback-Seite. Der Quellcode ist
> privat. Stillfeed ist ein privates Heimprojekt, keine kommerzielle App.

## Installieren

1. Unter [**Releases**](../../releases) die neueste Version öffnen.
2. Die passende Datei laden:
   - **`stillfeed-<version>-arm64.apk`** – für aktuelle Android-Geräte (empfohlen).
   - `stillfeed-<version>-arm32.apk` – für ältere 32-Bit-Geräte.
   - `stillfeed-<version>.apk` – läuft auf allen Geräten, ist aber größer.
3. Die APK auf dem Gerät öffnen und die Installation aus „unbekannter
   Quelle“ einmalig erlauben.
4. Updates lassen sich direkt über eine bestehende Installation legen, ohne
   vorher zu deinstallieren.

## Was die App kann

- **Vier Plattformen, ein Fenster**, mit sofortigem Wechsel; einzelne
  Plattformen abschaltbar, Startplattform wählbar.
- **Werbung, Vorschläge und Reels** werden ausgeblendet.
- **Read-only:** keine Posten-, Antworten- oder Teilen-Knöpfe; Reaktionen
  per Schalter abschaltbar.
- **Facebook-Messenger** bleibt voll nutzbar, inklusive Bildversand –
  in den Einstellungen abschaltbar, dann ist auch er nur zum Lesen.
- **Cookie-Abfragen** der Plattformen werden nicht mehr weggeblendet; du
  entscheidest selbst über die Cookies.
- **Fingerabdruck-Sperre**, erzwingbarer Dark Mode, old.reddit-Option,
  Bild-Download per langem Tippen, Nur-Text-Ansicht für externe Links.
- **Datensparsam:** kein Server, keine Analyse, kein automatischer
  Kontozugriff.

## Bekannte Probleme (Stand 0.42.0)

Ein Heimprojekt, im Alltag stabil, aber nicht überall zu 100 % perfekt:

- **Instagram:** Ausgeblendete Anzeigen hinterlassen eine leere Lücke mit
  dem Hinweis „Anzeige ausgeblendet“. Ein optionaler Einklappmodus in den
  Einstellungen verkleinert sie (experimentell).
- **X:** Das erste Video direkt nach dem Kaltstart bleibt gelegentlich kurz
  schwarz und lädt sich dann nach wenigen Sekunden selbst neu.
- **Facebook:** Vereinzelt lädt ein Bild erst beim Öffnen des Beitrags.
- **Filter:** Direkt nach dem Laden dauert es einen Sekundenbruchteil, bis
  Knöpfe verschwinden. Nicht jede Werbung wird sofort erkannt; die Filter
  werden zentral nachgezogen, ohne dass es eine neue APK braucht.

## Feedback und Wünsche

Fehler oder Ideen gern als [**Issue**](../../issues) melden. Bei
Darstellungsfehlern hilft ein Screenshot. Kleine Wünsche (weitere
Filter-Stichwörter, Schalter, Bedien-Verbesserungen) nehme ich gern auf;
große Umbauten wie Posten oder Konten-Verwaltung sind bewusst nicht das Ziel.

## Lizenz

Alle Rechte vorbehalten. Der Quellcode ist nicht öffentlich; die
bereitgestellten APKs sind nur zum privaten Gebrauch gedacht.
