# Walking Tours

A small, growing collection of single-page, bilingual (English / Portuguese)
self-guided open-air city walking tours. Each tour is an interactive map with a
story per stop, walking times and one-tap Apple Maps navigation.

- `index.html` — the hub that lists the available tours.
- `berlin/` — **Berlin in the Open Air**: the open-air heart of the city on
  foot from a single parking at Alexanderplatz, ending at Hauptbahnhof with a
  short train ride back to the car. 14 walking stops plus 3 optional side-trips
  (East Side Gallery, Victory Column, Bernauer Wall Memorial).

Language follows the device (`navigator.language`) and can be toggled manually.

## Add a new tour

Create a folder next to `berlin/` with its own `index.html`, then add a card to
the `tours` list in the hub `index.html`.

## Credits

- Map tiles © Esri.
- Icons from [Font Awesome Free](https://fontawesome.com/) (CC BY 4.0).
- Fonts: Cinzel, Spectral, Archivo (Google Fonts).
