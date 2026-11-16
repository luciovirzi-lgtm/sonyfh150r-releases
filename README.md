# Sony FH 150R

*An mp3 player with a classic design — a macOS music player, web radio and recorder whose window is a photo of the 1980s Sony FH-150R hi-fi stack.*

Lettore musicale per macOS ispirato all'impianto Sony FH-150R: la finestra **è** la fotografia dell'impianto e ogni tasto, manopola e cursore funziona.

## Funzioni

- **Lettore CD** — MP3 con riproduzione gapless, display VFD a 7 segmenti e matrice di punti, shuffle, repeat.
- **Tuner** — web radio (Icecast/Shoutcast e HLS, MP3/AAC) con ricerca su [Radio Browser](https://www.radio-browser.info), 10 preset, LCD a 14 segmenti con imitazione RDS (PS, PTY, RadioText).
- **Amplificatore** — analizzatore di spettro a 7 bande, volume, muting, AMFB simulato (bassi profondi), selezione sorgente.
- **Equalizzatore** grafico a 7 bande con preamp, balance e preset.
- **Piastra** — playlist nella finestra della cassetta (con bobine animate), import/export M3U, registrazione della radio in MP3 (LAME).
- Manuale d'uso integrato (clic sulla scritta FH-150R o ⌘?).

## Requisiti

macOS 13 o successivo (Intel o Apple Silicon). Per compilare: Xcode 15, [XcodeGen](https://github.com/yonaskolb/XcodeGen), Python 3 con Pillow e NumPy (solo per rigenerare le immagini).

## Note legali

Progetto personale, non affiliato né approvato da Sony. Sony, FH-150R e la fotografia dell'impianto appartengono ai rispettivi proprietari. L'encoder MP3 LAME è distribuito con licenza GNU LGPL (vedi `tools/build_lame.sh`).
