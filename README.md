# Snake 3D

Een 3D-versie van het klassieke Snake, in één HTML-bestand. Niets te installeren.

## Spelen

Open `index.html` in een browser. Het spel laadt [Three.js](https://threejs.org/) via een CDN, dus je hebt de eerste keer een internetverbinding nodig.

## Besturing

| Toets | Actie |
| --- | --- |
| Pijltjes of WASD | Sturen |
| X of + | Sneller |
| Z of − | Langzamer |
| Spatie | Pauze |
| Enter | Opnieuw beginnen |

## Spelregels

- Eet de sinaasappels om te groeien en punten te scoren.
- Raak je een muur of je eigen lichaam, dan is het game over.
- De snelheid stel je zelf in (1 t/m 10); het spel versnelt niet vanzelf.
- Je beste score wordt in je browser bewaard.

## Techniek

- Eén bestand: `index.html` (HTML, CSS en JavaScript)
- 3D-weergave met Three.js 0.160.0 (via jsDelivr)
- Bord van 20 × 20 vakjes
