# felix-piepenbrock.de

Statische Website von Felix Piepenbrock (Online-Marketing-Beratung, SEO, Content, Newsletter).

- Kein Build-Schritt: reines HTML/CSS, ausgeliefert über Cloudflare Pages (Build-Befehl leer, Ausgabeordner `/`).
- Schriften (Inter, SIL Open Font License) liegen lokal in `fonts/`, keine externen Dienste.
- News-Artikel liegen in `news/`. Neuer Artikel: Datei kopieren, Inhalt anpassen, in `news/index.html`, auf der Startseite und in `sitemap.xml` verlinken.
- In Cloudflare keine Web Analytics / Zaraz aktivieren, sonst stimmt die Datenschutzerklärung („kein Tracking“) nicht mehr.

## Offene Punkte vor dem Livegang

- USt-ID im Impressum eintragen oder den Abschnitt entfernen (gelb markiert in `impressum.html`).
- Datenschutzerklärung prüfen lassen (Entwurfshinweis danach entfernen).
- Cloudflare Pages einrichten und Domain umstellen (E-Mail-DNS-Einträge unverändert lassen).
