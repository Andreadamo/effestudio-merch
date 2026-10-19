# Merch Effestudio

Pagine statiche (GitHub Pages) per il merchandising di Effestudio Training Center.

- `index.html` — catalogo clienti: prenotazione, pagamento e ritiro in palestra
- `staff.html` — app staff installabile: scanner QR, prenotazioni, vendita banco, etichette
- `dashboard.html` — dashboard di controllo: incassi, metodi, magazzino, movimenti

I dati stanno nel Google Sheet "Inventario Merch Effestudio"; la web app Apps Script del foglio
risponde in JSON (`backend/Api.gs`). L'indirizzo è in `config.js`.
