<h1 align="center">NIGIN · Weltengenerator</h1>

<p align="center"><b><a href="https://marcohost33-maker.github.io/nigin-weltengenerator-studio/NIGIN_Weltengenerator_v0_6_0_Offline.html">▶ Im Browser spielen</a></b> &nbsp;·&nbsp; <b><a href="https://github.com/marcohost33-maker/nigin-weltengenerator-studio/releases/download/v0.6.0/NIGIN_Weltengenerator_v0_6_0_Offline.html">⬇ HTML herunterladen</a></b> &nbsp;·&nbsp; Version 0.6.0 · Vorschau</p>
<p align="center"><sub>Eine Datei · läuft offline · ohne Konto · die Welt sendet keine Daten</sub></p>

| Datei | Inhalt | Spielen | Download |
|---|---|---|---|
| **Weltengenerator** | Start in der Landschaftsansicht | [▶ spielen](https://marcohost33-maker.github.io/nigin-weltengenerator-studio/NIGIN_Weltengenerator_v0_6_0_Offline.html) | [⬇ HTML](https://github.com/marcohost33-maker/nigin-weltengenerator-studio/releases/download/v0.6.0/NIGIN_Weltengenerator_v0_6_0_Offline.html) |
| **Baukasten** | dasselbe Weltstudio, Start direkt im Hex-Baukasten | [▶ spielen](https://marcohost33-maker.github.io/nigin-weltengenerator-studio/NIGIN_Baukasten_v0_6_0_Offline.html) | [⬇ HTML](https://github.com/marcohost33-maker/nigin-weltengenerator-studio/releases/download/v0.6.0/NIGIN_Baukasten_v0_6_0_Offline.html) |

Das **Weltstudio** erzeugt eine 300 × 300 m grosse Landschaft (Aare, Wald, Tal) aus Parametern und einem Seed. Im **Landschaftssimulator** malst du Bodenarten, Pflanzen und Wasserquellen und lässt die Welt Schritt für Schritt weiterrechnen. Im **Baukasten** baust du von Hand: Jedes Sechseck hat eine Mitte und sechs Randsegmente. Welten lassen sich als JSON speichern und wieder laden, Ansichten als PNG exportieren.

## So startest du

1. **Direkt im Browser:** oben auf *Im Browser spielen* klicken. Fertig.
2. **Offline:** *HTML herunterladen*, dann die Datei mit Chrome, Edge, Firefox oder Safari öffnen. Es ist keine Installation nötig, nur JavaScript muss aktiv sein.
   - Auf iPhone und iPad zeigt die Vorschau der Dateien-App kein JavaScript. Die Datei dort über *Teilen* in einem Browser öffnen.

## Bedienung

- Werkzeug wählen und auf die Karte tippen · **↶ / ↷** rückgängig und wiederholen
- **Datei**-Menü: Welt als JSON speichern und laden, Ansicht als PNG

## Was es ist und was (noch) nicht

- Stilisiert und frei erfunden, keine Geodaten und keine Hydrauliksimulation.
- Entwicklungsansicht (0.x): Einige Prüf- und Diagnosefunktionen und interne Statusmarken sind sichtbar.
- Auf schmalen Bildschirmen (Handy) ist das Datei-Menü noch nicht erreichbar; Speichern und Laden ab Tablet-Breite.

## Datenschutz

- Die Welt läuft vollständig lokal; die Datei lädt nichts nach und baut von sich aus keine Netzwerkverbindungen auf.
- Beim Spielen über *Im Browser spielen* liefert GitHub Pages die Datei aus und verarbeitet dabei, wie jeder Webserver, Zugriffsdaten (etwa die IP-Adresse). Mit der heruntergeladenen Datei entfällt auch das.
- Speichern erfolgt über Dateien, die du selbst herunterlädst. Es gibt keinen Browserspeicher.
- Keine Konten, keine Cookies, keine Analyse oder Werbung.

## Prüfsumme

Die Dateien in diesem Repository und im Release sind byte-gleich. SHA-256 (auch in `SHA256SUMS.txt`):

```
42fed12809bfdd07336b16eee064415c66db5230ad6f5b72cef67b6c6131d657  NIGIN_Weltengenerator_v0_6_0_Offline.html
465043b6da84eebd8d095e4714cf40cf89e78a68bbf322dee1dd9728e5c37be7  NIGIN_Baukasten_v0_6_0_Offline.html
```

## Lizenz

Kostenlos spielen und unverändert nicht-kommerziell weitergeben ist erlaubt, mit Herkunftsangabe. Alles Weitere regelt die [NIGIN Spielnutzungs-Lizenz](LICENSE.md).

## Die NIGIN-Welten

Nigin ist ein Füchslein, das mit Tierwesen durch verschiedene Welten zieht. Jede Welt ist eine eigene, offline spielbare Datei:

- [Drei Wesen](https://github.com/marcohost33-maker/nigin-drei-wesen), Fuchs, Rabe und Geist in einer kleinen 3D-Welt · [▶ spielen](https://marcohost33-maker.github.io/nigin-drei-wesen/)
- [Hauswelt](https://github.com/marcohost33-maker/nigin-hauswelt), Atelierhaus und Aarewelt zum Erkunden in 3D · [▶ spielen](https://marcohost33-maker.github.io/nigin-hauswelt/)
- [Wasserwelt](https://github.com/marcohost33-maker/nigin-wasserwelt), interaktive 3D-Wasserwelt mit Wetter und Unterwasser · [▶ spielen](https://marcohost33-maker.github.io/nigin-wasserwelt/)
- **Weltengenerator**, Landschaften aus Parametern und Hex-Baukasten *(du bist hier)*
- [Städtegenerator](https://github.com/marcohost33-maker/nigin-staedtegenerator), Stadtgenerator mit Comic-Studio und Missionen · [▶ spielen](https://marcohost33-maker.github.io/nigin-staedtegenerator/)
- [Vegetation Lab](https://github.com/marcohost33-maker/nigin-vegetation-lab), Wiese und Kornfeld auf Hexfeldern, mit Wind · [▶ spielen](https://marcohost33-maker.github.io/nigin-vegetation-lab/)

<sub>Coworker Research / Coworkerz · gebaut als Mensch-plus-KI-Zusammenarbeit</sub>
