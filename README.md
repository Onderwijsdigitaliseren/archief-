# Het Nachtdossier

Een schil rond losse interactieve moordmysteries. Elke zaak is een op zichzelf staand HTML-bestand; `index.html` is alleen de recherchekamer die ernaar linkt.

## Zaken
- `MERIDIAAN___Nachtdossier44-C.html` — Villa Meridiaan
- `nachtfrequentie.html` — Nachtfrequentie (92.4 FM)
- `nachttrein212.html` — Nachttrein 212 (Amsterdam · Wenen)

## Online zetten (GitHub Pages)
1. Zet alle bestanden in de root van je repo.
2. Repo → **Settings → Pages** → Source: `Deploy from a branch`, branch `main`, map `/root`.
3. Na een minuut staat de schil op `https://<gebruiker>.github.io/<repo>/`.

## Nieuwe zaak toevoegen
Open `index.html`, zoek de `ZAKEN`-array bovenin de `<script>` en voeg één object toe:

```js
{ nummer: "Zaak 03", titel: "...", omschrijving: "...", bestand: "jouwbestand.html", stempel: "Onopgelost" }
```

Zet het bijbehorende `.html`-bestand ernaast. Klaar.
