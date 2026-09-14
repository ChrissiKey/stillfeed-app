<p align="center">
  <img src="icon.png" width="120" alt="Stillfeed">
</p>

# Stillfeed

**Reddit, X, Facebook und Instagram – in einer App, nur zum Lesen.**
*Enjoy the (fast) silence.*

Stillfeed bündelt vier soziale Netzwerke in einer ruhigen App zum Lesen.
Werbung, Vorschlagsbeiträge, Reels, Storys und Spaces werden ausgeblendet;
Posten, Kommentieren und Reaktionen sind ab Werk gesperrt. Wer möchte,
schaltet Reaktionen oder den Facebook-Messenger in den Einstellungen frei.

> Dies ist die öffentliche Download- und Feedback-Seite. Der Quellcode ist
> privat. Stillfeed ist ein privates Heimprojekt, keine kommerzielle App.

## So sieht es aus

<p align="center">
  <img src="screenshots/start.png" width="31%" alt="Startbildschirm">
  <img src="screenshots/feed.png" width="31%" alt="Feed-Ansicht (Demo)">
  <img src="screenshots/settings.png" width="31%" alt="Einstellungen">
</p>

<p align="center"><sub>Startbildschirm · Feed-Ansicht (Demo mit Platzhalter-Inhalt) · Einstellungen</sub></p>

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
- **Werbung, Vorschläge, Reels, Storys** (Facebook) und **Spaces** (X)
  werden ausgeblendet.
- **Streng zum Lesen ab Werk:** keine Posten-, Antworten- oder Teilen-Knöpfe;
  Liken/Reagieren ist voreingestellt gesperrt, der Facebook-Messenger ist aus.
  Beides lässt sich in den Einstellungen freischalten.
- **Facebook-Messenger** (in den Einstellungen aktivierbar): dann voll
  nutzbar inklusive Bildversand. Solange er aus ist, steht an seiner Stelle
  ein durchgestrichenes, nicht klickbares Symbol.
- **Deutsch oder Englisch** – Sprache oben rechts im Startbildschirm oder in
  den Einstellungen umschaltbar (nur die App-Oberfläche).
- **Cookie-Abfragen** der Plattformen werden nicht mehr weggeblendet; du
  entscheidest selbst über die Cookies.
- **Fingerabdruck-Sperre**, erzwingbarer Dark Mode, old.reddit-Option,
  Bild-Download per langem Tippen, Nur-Text-Ansicht für externe Links.
- **Datensparsam:** kein Server, keine Analyse, kein automatischer
  Kontozugriff.

## Bekannte Probleme (Stand 0.47.0)

Ein Heimprojekt, im Alltag stabil, aber nicht überall zu 100 % perfekt:

- **Reddit:** Direkt nach dem Start sind Beiträge manchmal noch nicht
  anklickbar – ein kurzes Wischen behebt es sofort. Beim Öffnen eines
  Beitrags dauert es kurz (unter einer Sekunde), bis der Posten-/Antworten-
  Knopf verschwindet. GIFs starten nicht von selbst.
- **X:** Ein Beitrag oder Video braucht gelegentlich einen kurzen Moment zum
  Laden. Fotos und Bilder werden problemlos angezeigt.
- **Facebook:** Das Antwortfeld ist beim Öffnen kurz sichtbar, bevor es
  ausgeblendet wird (wie bei Reddit). Manche Bilder im Feed sind links und
  rechts minimal beschnitten (leichter Overscan).
- **Instagram:** Nach dem Ausblenden einer Anzeige bleibt eine kleine dunkle
  Lücke stehen (stört im Alltag kaum). Werbung wird nicht immer sofort
  erkannt; beim schnellen Scrollen kann das auffallen. Ein optionaler
  Einklappmodus in den Einstellungen verkleinert die Lücke (experimentell).
- **Filter:** Nicht jede Werbung wird sofort erkannt; die Filter werden
  zentral nachgezogen, ohne dass es eine neue APK braucht.

## Feedback und Wünsche

Fehler oder Ideen gern als [**Issue**](../../issues) melden. Bei
Darstellungsfehlern hilft ein Screenshot. Kleine Wünsche (weitere
Filter-Stichwörter, Schalter, Bedien-Verbesserungen) nehme ich gern auf;
große Umbauten wie Posten oder Konten-Verwaltung sind bewusst nicht das Ziel.

## Lizenz

Alle Rechte vorbehalten. Der Quellcode ist nicht öffentlich; die
bereitgestellten APKs sind nur zum privaten Gebrauch gedacht.
