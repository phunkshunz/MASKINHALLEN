# Phunkshunz AUDIO · MASKINHALLEN

Hemsida för Phunkshunz AUDIO och techno-serien MASKINHALLEN. Ligger på GitHub Pages: phunkshunz.github.io/maskinhallen

- `index.html` är hela sidan (en fil: HTML, CSS, demos och skript).
- `site.html` skickar bara vidare till `index.html`.

## Ändra saker

- **Köplänkar:** överst i skriptet, `const SHOP = { … }`. En plugg utan länk visar "Coming soon".
- **Produktbilder:** laddas direkt från Payhip. Byter du bild i Payhip får bilden en ny adress, och då behöver adressen i `index.html` bytas (sök på `pe56d.s3.amazonaws.com`).
- **Swish:** skriv ditt nummer i `SWISH = { number: "" }`. Står det tomt visas ingen Swish-knapp. Priserna i kronor står i samma ruta.
- **Demos:** BETONG, ARMERING och FUKT kan spelas i webbläsaren (öppnas under varje plugg).
