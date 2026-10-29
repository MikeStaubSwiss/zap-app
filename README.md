# ZAP-App – Zoom and Print

Bild scannen, vergrössern und auf mehrere A4-Seiten verteilen. Das Ergebnis ist ein PDF zum Ausdrucken und Zusammenkleben – ideal für Poster, Vorlagen oder Pläne.

Alles läuft direkt im Browser. Es wird nichts hochgeladen, das Bild bleibt auf dem Gerät.

## Funktionen

- **Bild scannen** mit der Handykamera oder aus der Galerie wählen (auch Drag & Drop und Einfügen)
- **Drehen** in 90°-Schritten
- **Grösse festlegen** über
  - **Seitenanzahl** (2–20 Seiten, Raster und Ausrichtung werden automatisch optimiert) oder Spalten × Zeilen von Hand
  - **Prozent** (25–1000 %, 100 % = Bild füllt genau eine A4-Seite); die nötige Seitenzahl wird berechnet
- **Hoch- oder Querformat**, «Ganzes Bild» oder «Seiten füllen»
- **Druckrand** und **Klebezugabe** (Überlappung) einstellbar
- **Klebelinien und Seitencodes** (A1, A2, B1 …) auf jeder Seite
- **Vorschau** des ganzen Posters und jeder einzelnen PDF-Seite
- **Anzeige** von Postergrösse in cm, Vergrösserung in % und Druckauflösung in dpi mit Warnung bei zu geringer Schärfe
- **PDF-Export** mit bis zu 200 dpi

## Benutzung

1. Bild scannen oder wählen.
2. Seitenanzahl oder Prozent wählen.
3. Vorschau prüfen.
4. «PDF erstellen und speichern» antippen.
5. PDF öffnen und mit **100 % / «Tatsächliche Grösse»** drucken – nicht «An Seite anpassen», sonst stimmen die Klebelinien nicht.
6. Blätter nach Code (A1, A2 …) zusammenlegen, an den gestrichelten Linien überlappen und kleben.

## Auf GitHub Pages veröffentlichen

1. Neues Repository anlegen und `index.html` sowie `README.md` hochladen.
2. Unter **Settings → Pages** bei «Source» den Branch `main` und den Ordner `/ (root)` wählen.
3. Nach kurzer Zeit ist die App unter `https://<benutzername>.github.io/<repository>/` erreichbar.

Lokal genügt es, `index.html` im Browser zu öffnen.

## Technik

- Eine einzige Datei: HTML, CSS und JavaScript ohne Build-Schritt
- PDF-Erzeugung mit [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 (über cdnjs)
- Schriften: Archivo, IBM Plex Sans, IBM Plex Mono (Google Fonts)
- Helles und dunkles Design folgt der Systemeinstellung
