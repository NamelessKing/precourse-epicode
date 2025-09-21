# Challenge 1 – Pagina di Presentazione

Requisito: creare una pagina HTML con immagine personale, lista hobby/interessi, contatti. Extra: tabella esperienze; pubblicare su GitHub.

## Requisiti Base (Richiesti) & Stato

- Immagine personale: ✅ (`figure` + `img` + `figcaption`)
- Lista hobby / interessi: ✅ (`ul` con 4 elementi)
- Contatti (email, telefono, socials): ⚠️ Parziale
  - GitHub: ✅ link
  - LinkedIn: ✅ link
  - Email: mostrata come "su richiesta" (placeholder, non reale)
  - Telefono: NON incluso (privacy) – chiarito qui

## Extra (Facoltativi) & Stato

- Tabella esperienze scolastiche / lavorative: ✅ con `caption`, `thead`, `tbody`, `th scope="row/col"`, date in `<time>`
- Pubblicazione su GitHub: ✅ (progetto presente nel repository)

## Dettagli Implementazione

- Landmark semantici: `header`, `main`, `footer` + 3 `section`
- Skip link tastiera (`.skip-link`) → accesso diretto a `main`
- Focus outline definito in CSS (accessibilità base)
- Favicon SVG (`assets/img/favicon.svg`)
- CSS semplice: layout contenuto centrato, tabella leggibile
- JS: placeholder (`main.js`) senza logica

## Struttura File

```text
index.html
css/style.css
js/main.js
assets/img/me.jpg
assets/img/favicon.svg
assets/img/screenshot.png (placeholder)
```

## Note su Privacy Contatti

Telefono ed email non sono esposti per scelta. Se necessario, si possono aggiungere:

```html
<a href="mailto:tuonome@example.com">tuonome@example.com</a>
<a href="tel:+391234567890">+39 123 456 7890</a>
```

## TODO (Unico Aperto)

- Ottimizzare immagine profilo (`me.jpg` → `me.webp` < 80KB).

## Come Avviare

Apri `index.html` in un browser (nessuna build, nessuna dipendenza).

## Verifica Rapida Completamento

- Contenuti base presenti (eccetto telefono / email esplicita per scelta) ✔
- Extra implementati ✔
- Semantica e accessibilità minima ✔

## Screenshot

`assets/img/screenshot.png` (da aggiornare quando pronto).

## License / Uso

Uso didattico interno (nessuna licenza ancora definita).
