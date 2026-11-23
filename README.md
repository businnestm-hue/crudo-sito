# Sito di Crudo

Sito statico (HTML + CSS, nessun framework): `index.html`, `menu.html`, `vini.html`, `contatti.html`, `css/style.css`, `img/`.
Tutti i dati vengono da `../contenuti.md` (fonti: Google Maps, Canva, Instagram @crudoforli).

## Vederlo in locale
Da questa cartella:
```
python -m http.server 8000
```
e apri http://localhost:8000

## Aggiornarlo
1. Modifica `../contenuti.md` (menu, vini, orari).
2. Chiedi a Claude Code di aggiornare le pagine e di far girare il subagent `revisore-sito`.
3. Controlla, fai il commit, poi pubblica (lo fa una persona, non un'automazione).

## Foto
Sono a 640×640 (prese da Instagram). Per una qualità migliore sostituiscile con gli originali, mantenendo lo stesso nome file.
