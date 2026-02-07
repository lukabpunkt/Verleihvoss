# Verleih Voss – Website

Website für Gyrosgrill-Vermietung (Verleih Voss, Lingen-Holthausen).

## Deployment auf GitHub Pages

1. **Repository:** Alle Dateien in das Repo [lukabpunkt/Verleihvoss](https://github.com/lukabpunkt/Verleihvoss) pushen.

2. **Startseite für GitHub Pages:**  
   GitHub Pages nutzt standardmäßig `index.html` als Startseite.  
   - Entweder die Datei `index.html.html` im Repo in `index.html` **umbenennen**,  
   - oder eine Kopie als `index.html` ablegen (Inhalt = gleicher Inhalt wie `index.html.html`).

3. **GitHub Pages aktivieren:**
   - Im Repo: **Settings** → **Pages**
   - Unter **Source**: **Deploy from a branch**
   - **Branch:** `main` (oder `master`), Ordner: **/ (root)**
   - Speichern

4. **Nach dem Deployment:**  
   Die Seite ist erreichbar unter:  
   **https://lukabpunkt.github.io/Verleihvoss/**

Die Seite passt Bildpfade und die Links zu Impressum/Datenschutz automatisch an, wenn sie unter `*.github.io` läuft.

## Dateien im Repo (Empfehlung)

- `index.html` (Startseite; aus `index.html.html` erzeugen/umbenennen)
- `impressum.html`
- `datenschutz.html`
- `Logo.png` (Logo, kleingeschrieben je nach System)
- `B1.avif` … `B6.avif` (Diashow-Bilder)
- `.nojekyll` (bereits angelegt, verhindert Jekyll-Verarbeitung)
