# Immagini delle email della suite

Cartella pubblica neutra delle immagini delle email (parametro `@ImageBaseURL` dell'installazione:
`https://raw.githubusercontent.com/acappelletti/images/main/suite/`). I nomi dei file non sono scritti nel codice:
si passano con `@HeaderLogoImage`, `@HeaderMascotImage`, `@TitleMascotImage` e `@FooterLogoImage`; un nome NULL toglie
l'immagine dall'email. PNG con fondo trasparente, al doppio della dimensione mostrata.

| File | Mostrato (px) | Parametro | Dove |
|---|---|---|---|
| `header_scritta.png` | 282 × 75 | `@HeaderLogoImage` | Testata, a sinistra: scritta e payoff |
| `header_mascotte_alto.png` | 154 × 133 | `@HeaderMascotImage` | Testata, a destra: parte alta della mascotte |
| `header_mascotte_basso.png` | 154 × 19 | `@TitleMascotImage` | Banda del titolo, a destra: parte bassa della mascotte |
| `footer_logo_blu.png` | 100 × 39 | `@FooterLogoImage` | Piè di pagina su fondo blu |
| `footer_logo.png` | 100 × 39 | `@FooterLogoImage` | Piè di pagina su fondo chiaro |
| `custom/header_banner.jpg` | 758 × 147 | `@HeaderImageURL` | Banner al posto di tutta la testata (prova) |
| `custom/footer_banner.jpg` | 758 × 136 | `@FooterImageURL` | Immagine al posto di tutto il piè di pagina (prova) |
