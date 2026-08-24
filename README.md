# Galgenmännchen

Ein kleines Galgenmännchen-Spiel für Kinder der **1. und 2. Klasse**, vollständig statisch und direkt für GitHub Pages geeignet.

## Dateien

- `index.html` – das komplette Spiel
- `woerter.txt` – Wortliste, **ein Wort pro Zeile**

## Wortliste ändern

Einfach `woerter.txt` bearbeiten:

```text
HAUS
MAUS
SONNE
BALL
KATZE
```

Leerzeilen werden ignoriert. Zeilen, die mit `#` beginnen, können als Kommentare benutzt werden.

```text
# Tiere
HUND
KATZE
MAUS
```

Danach nur committen/pushen – GitHub Pages verwendet automatisch die neue Liste.

## GitHub Pages

1. Dateien ins Repository legen.
2. **Settings → Pages**
3. **Deploy from a branch**
4. Branch `main`, Ordner `/ (root)`
5. Speichern

Es gibt keinen Build-Prozess und keine externen Abhängigkeiten.


## Spielablauf

Der Galgen wird bei Fehlern Schritt für Schritt aufgebaut. Insgesamt sind 11 Fehlversuche möglich.
