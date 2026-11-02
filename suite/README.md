# Immagini delle email della suite

Cartella pubblica delle immagini delle email della suite SQL Server HTML Email Notifications. Una sottocartella per
marchio: **`flycheck/`** è quella predefinita (parametro `@ImageBaseURL` dell'installazione,
`https://raw.githubusercontent.com/acappelletti/images/main/suite/flycheck/`); `custom/<cliente>/` contiene le immagini
personalizzate di un cliente o di una prova (banner al posto della testata e del piè di pagina). Per un nuovo marchio si crea
un'altra cartella e si passa il suo indirizzo all'installazione.

I nomi dei file non sono scritti nel codice: si passano con `@HeaderLogoImage`, `@HeaderMascotImage`, `@TitleMascotImage` e
`@FooterLogoImage` (un nome NULL toglie l'immagine dall'email); i banner con l'URL completo in `@HeaderImageURL` e
`@FooterImageURL`. PNG con fondo trasparente, al doppio della dimensione mostrata.

## suite/flycheck (predefinita)

| Anteprima | File | Mostrato (px) | Parametro | Dove |
|---|---|---|---|---|
| <img src="flycheck/header_scritta.png" width="282" alt="header_scritta.png"> | `header_scritta.png` | 282 × 75 | `@HeaderLogoImage` | Testata, a sinistra: scritta e payoff |
| <img src="flycheck/header_mascotte_alto.png" width="154" alt="header_mascotte_alto.png"> | `header_mascotte_alto.png` | 154 × 133 | `@HeaderMascotImage` | Testata, a destra: parte alta della mascotte |
| <img src="flycheck/header_mascotte_basso.png" width="154" alt="header_mascotte_basso.png"> | `header_mascotte_basso.png` | 154 × 19 | `@TitleMascotImage` | Banda del titolo, a destra: parte bassa della mascotte |
| <img src="flycheck/footer_logo_blu.png" width="100" alt="footer_logo_blu.png"> | `footer_logo_blu.png` | 100 × 39 | `@FooterLogoImage` | Piè di pagina su fondo blu (predefinito) |
| <img src="flycheck/footer_logo.png" width="100" alt="footer_logo.png"> | `footer_logo.png` | 100 × 39 | `@FooterLogoImage` | Piè di pagina su fondo chiaro (scritta chiara: su una pagina bianca si vede poco) |

## suite/custom/retiarius

Banner di prova del marchio Retiarius, da passare con l'URL completo.

| Anteprima | File | Mostrato (px) | Parametro | Dove |
|---|---|---|---|---|
| <img src="custom/retiarius/header_banner.jpg" width="380" alt="header_banner.jpg"> | `header_banner.jpg` | 758 × 147 | `@HeaderImageURL` | Banner al posto di tutta la testata |
| <img src="custom/retiarius/footer_banner.jpg" width="380" alt="footer_banner.jpg"> | `footer_banner.jpg` | 758 × 136 | `@FooterImageURL` | Immagine al posto di tutto il piè di pagina |

Indirizzi completi:
`https://raw.githubusercontent.com/acappelletti/images/main/suite/custom/retiarius/header_banner.jpg` e
`https://raw.githubusercontent.com/acappelletti/images/main/suite/custom/retiarius/footer_banner.jpg`.
