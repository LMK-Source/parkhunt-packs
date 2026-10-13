# Park Hunt: offline state packs

Static, versioned data files that the **Park Hunt** iOS app downloads one state at a time: state, county, city and
other public parks, plus trails, for offline use. Built by `packs/scripts/build_pack.py` in the app repo.

Download URLs (rolling release `v1`): `https://github.com/LMK-Source/parkhunt-packs/releases/download/v1/<ST>-<file>`,
index: `…/v1/index.json`. Every file is listed with its sha256 in `<ST>-manifest.json`; the app verifies each file.

## Sources and licences
- **Park boundaries:** U.S. Geological Survey (USGS) Gap Analysis Project (GAP), 2024, *Protected Areas Database of the
  United States (PAD-US) 4.1*, https://doi.org/10.5066/P96WBCHS: **public domain**.
- **Trails:** National Park Service Public Trails; USDA Forest Service National Forest System Trails: US federal
  government works.
- **Places:** US Census Bureau TIGERweb: public domain.
- **OpenStreetMap-derived files** (`*-osm.json.gz`): © OpenStreetMap contributors. This derivative database is made
  available under the **Open Database License (ODbL 1.0)**: https://opendatacommons.org/licenses/odbl/1-0/ and
  https://www.openstreetmap.org/copyright. Public-domain and ODbL data are never mixed in one file.

Not affiliated with or endorsed by the National Park Service or any state or local park agency.
