# Torneo Calcetto Capodacqua - sito pronto corretto

Versione corretta per GitHub Pages.

## Correzioni incluse

- Menu hamburger laterale corretto: chiuso di default, si apre solo con il pulsante menu.
- Pagina squadra corretta: mostra logo, nome, La rosa, allenatore, statistiche e partite.
- Dati 2025 reintegrati: squadre, roster, risultati, classifiche e tabellone.
- Locandina finale inserita nel sito in versione web e A4 JPG.
- Struttura pronta per pubblicazione statica su GitHub Pages.

## Pubblicazione

1. Estrai lo ZIP.
2. Carica il contenuto interno nella root del repository GitHub.
3. Non caricare la cartella esterna.
4. In GitHub Pages usa branch `main` e cartella `/root`.

## File importanti

- `index.html`: home
- `team.html`: pagina automatica squadra, esempio `team.html?id=fc-amburgo&year=2025`
- `data/teams-2025.json`: roster squadre 2025
- `data/matches-2025.json`: partite 2025
- `assets/img/posters/locandina-2026-finale-web.jpg`: locandina sito
- `assets/img/posters/locandina-2026-finale-a4.jpg`: locandina stampa


## Locandina finale
Nel sito è integrata solo la locandina finale fornita dall'utente: `assets/img/posters/locandina-2026-finale-web.jpg`. La versione stampa è `assets/img/posters/locandina-2026-finale-a4.jpg`.
