# RechnerGAL – Persönliche Notiz (NICHT auf GitHub hochladen!)

Diese Datei ist nur für dich. Sie beschreibt auch die versteckten Funktionen –
wenn die auf GitHub landet, sind sie nicht mehr versteckt.

---

## 1. Stromrechner (⚡)
Berechnet den nötigen Strom, um bei einer neuen Bandgeschwindigkeit die
Ziel-Schichtdicke zu erreichen – auf Basis eines bekannten Ist-Zustands.
Rechnet automatisch bei jeder Eingabe neu (kein Button).

**Versteckt:** 5× auf das Ergebnisfeld tippen (alle 5 Klicks innerhalb von
10 Sekunden) → öffnet das **Mess-Protokoll**.
- Hier trägst du ein: Strom vorher/nachher, Schichtdicke vorher/nachher,
  optional Bandgeschwindigkeit und Notiz.
- Zweck: Sammlung echter Messpunkte für eine spätere, genauere Kurven-Berechnung
  (statt der aktuellen reinen Verhältnisrechnung).
- Einträge werden nur lokal auf dem jeweiligen Gerät gespeichert (Browser-Speicher).
- Button "📋 Alle kopieren" kopiert alle Einträge als Text – z. B. um sie mir
  in einem Chat zu schicken.

## 2. Zeitrechner (⏱️)
Berechnet die Laufzeit zwischen zwei Punkten der Anlage bei gegebener
Bandgeschwindigkeit. Zeigt außerdem Tageswitz, Zitat des Tages und die
nächsten Spiele der Lieblingsvereine an. Rechnet automatisch bei jeder Eingabe.

**Versteckt:** 5× auf das grüne Ergebnisfeld tippen (alle 5 Klicks innerhalb
von 10 Sekunden) → öffnet die **Gehalt-Seite**.
- Zeigt eine kurze Erklärung, dass es nur eine Weiterleitung ist, dann einen
  Button zum ADP-Lohnabrechnungs-Login.
- Kein Button in der Kopfzeile dafür – bewusst nur über diesen Trick erreichbar.

## 3. Spulenrechner (🧵)
Zwei Methoden (oben umschaltbar):
- **Nach Durchmesser:** Misst den Abstand vom Spulenrand bis zum Material
  (nicht bis zum Kern!). Referenzmessung + Stückzahl kalibrieren, danach
  reicht die aktuelle Messung. Hat einen sichtbaren Hilfe-Button
  "❓ Wie funktioniert das?" mit bebilderter Schritt-für-Schritt-Erklärung.
- **Nach Gewicht:** Vollgewicht + Stückzahl (Lieferschein) als Referenz,
  dann einfach das aktuelle Gewicht eintragen. Merkt sich Vollgewicht/Stückzahl
  automatisch (gerätespezifisch), nur das aktuelle Gewicht muss man jedes Mal
  neu eintragen.

Kein Button, keine Referenz-Kalibrierung übers Gerät hinweg – jedes Gerät
merkt sich seine eigenen Werte separat.

## 4. QR/Strichcode (🔳)
QR-Code erzeugen, Strichcode erzeugen, QR-Code per Kamera lesen. Passwort-Feld
zeigt standardmäßig Klartext (mit Augen-Symbol zum Ausblenden).

## 5. MDE-Anleitung (📱)
Läuft technisch als eigene Datei in einem anderen Repository (BandG), wird
hier nur eingebettet (iFrame). Neue Module bauen wir ab jetzt grundsätzlich
so – eigene Datei + iFrame, statt alles in eine Datei zu packen.

## 6. Besucherzähler (unten rechts, klein "#...")
Läuft über einen externen Gratis-Dienst (countapi.mileshilliard.com),
zählt geräteübergreifend. Zum manuellen Setzen auf einen neuen Wert:

`https://countapi.mileshilliard.com/api/v1/set/postmen1971-galvanik-tools-besucher?value=NEUEWERT`

Einfach im Browser öffnen, NEUEWERT durch die gewünschte Zahl ersetzen.

---

## Übersicht aller versteckten Zugänge
| Wo tippen | Wie oft/wie schnell | Was öffnet sich |
|---|---|---|
| Stromrechner-Ergebnisfeld | 5× in 10 Sek. | Mess-Protokoll |
| Zeitrechner-Ergebnisfeld (grün) | 5× in 10 Sek. | Gehalt-Seite (ADP-Link) |

## Sonstiges
- Datei heißt `index.html`, liegt im GitHub-Repository, läuft über
  postmen1971.github.io.
- Alle Eingaben/Kalibrierungen werden nur lokal im Browser des jeweiligen
  Geräts gespeichert – nichts syncronisiert sich zwischen Handy/Tablet/PC
  (außer dem Besucherzähler).
