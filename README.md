# traza

EUDR compliance and supply-chain traceability.

Bilingual static site: English at `/`, Spanish at `/es/`, sharing `assets/traza.css`.
No build step — it is plain HTML and CSS and can be served by any static host.

## Brand

Implemented from the supplied deck *BRANDING CAFE* (brand system v1.0, September 2026).

| Token | Value | Role |
| --- | --- | --- |
| Traza Red | `#E6342A` | primary signal |
| Ink | `#151515` | type and dark fields |
| Paper | `#F4F1EA` | warm neutral |
| Cobalt | `#2452FF` | logistics / movement |
| Teal | `#1F8A70` | verified / resolved |
| Ochre | `#C6922E` | processing / attention |

Type is Instrument Sans for communication and IBM Plex Mono for evidence
(IDs, coordinates, timestamps, labels), both from Google Fonts.

The **trace line** is the single visual device: line = continuity, node = event,
red node = verification, mono label = evidence. It appears as the orthogonal path
in the hero, the rail in the commodity list and the route in the scan cards.

The **eight chain icons** (origin, cooperative, harvest, processing, batch,
transport, point of sale, evidence) are redrawn as inline SVG on a common stroke.

## Status of the brand

The source deck is marked **PROPOSAL · NOT APPROVED** and **PENDING APPROVAL**
on its cover and on every applications slide. Its own "what we propose to
validate" list is: existing logo, corporate red, trace line, image direction and
typographic voice; final measurements, variants, interfaces, packaging and
production guides are explicitly left until after approval. This site implements
the proposal — it does not mean the proposal has been signed off.

## Known gaps

- **Logo.** No vector file was supplied. `assets/traza-lockup.png` and
  `assets/traza-wordmark.png` were extracted from the deck's master-red slide as
  alpha masks, painted with `currentColor` so the mark can render white, red or
  ink. Replace them with the original vector when it is available.
- **Photography.** The deck's imagery slide is captioned "conceptual image / to be
  replaced by real photography" and "no people or fictional places in the final
  version", so no photography is used here.
- **Content.** Batch numbers, origins and routes are illustrative, matching the
  deck's own example screens. The contact address is a placeholder.

## EUDR figures

Commodities, the due diligence statement mechanism and the application dates come
from the [European Commission's deforestation-free products page][ec]; the dates
reflect the December 2024 and December 2025 amendments. Sugar, cotton and tea are
*not* EUDR commodities — of the materials shown, only coffee is in scope.

[ec]: https://environment.ec.europa.eu/topics/forests/deforestation/regulation-deforestation-free-products_en
