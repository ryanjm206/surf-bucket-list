# Luke & Ryan's Surf Bucket List

Interactive map of surf trips from Sydney: routes, breaks, skill levels and crowd ratings.

## Adding photos
1. Put images in `photos/<spot-id>/` (e.g. `photos/bali/uluwatu.jpg`). Spot ids are in `index.html` (e.g. `bali`, `mentawai`, `telos`).
2. List them in `photos.json`:
```json
{ "bali": ["photos/bali/uluwatu.jpg"] }
```
3. Commit and push. The site updates in a minute or two.

Coastlines: Natural Earth. Map: Leaflet.
