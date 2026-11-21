# Carte hiver: winter tyre communes in France

Interactive, zoomable map of the French communes where winter equipment (winter tyres or carried chains/socks) is required from 1 November to 31 March under the *loi Montagne II* (décret 2020-1264).

**Live map:** https://gruslur.github.io/carte_hiver/

- `index.html`: the map (Leaflet + OpenStreetMap / CARTO tiles)
- `data/communes.js`: commune and department boundaries (TopoJSON) with obligation flags
- `sources/communes-status.csv`: flat list of communes and their status (4,017 required, 158 on part of the commune, 304 listed by loi-montagne.net but not in the official list)
- `sources/official-crosscheck.md`: sources and the cross-check against the official Sécurité routière list

Sources: commune lists per prefectoral order via loi-montagne.net; boundaries from IGN / france-geojson. Always check the prefecture's order for your department before travelling.
