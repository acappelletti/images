# suite/graphic

Elementi grafici neutri delle email della suite, uguali per tutti i marchi (nessun nome né logo).

| File | Uso |
|---|---|
| `thead.png` | Sfumatura delle intestazioni delle tabelle di listing (3 novembre 2026): 1 × 64 px, `#EEF1F5` in alto e, negli ultimi 27 px, la sfumatura della GIF di riferimento dell'autore fino a `#E1E3E6`. Si usa come `background:#EEF1F5 url(.../thead.png) 0 100%` sulle celle `<th>`, ancorata in basso; Outlook desktop mostra il colore pieno (`bgcolor`). Peso 101 byte. |
| `fold_tl.png`, `fold_tr.png`, `fold_bl.png`, `fold_br.png` | Pieghe a 45° della gabbia 3D (5 novembre 2026, `@3dEffect = 1`): 24 × 24 px mostrati a 12 px. Metà esterna nel grigio della pagina `#F4F6F8`, metà interna trasparente: si vede il `bgcolor` della cella, cioè il colore della banda del titolo (tl, tr: sotto la banda) o del piè di pagina (bl, br: sopra il piè) scurito. Valgono per qualsiasi colore. Circa 270 byte l'una. |

![thead.png ingrandita](thead.png)
