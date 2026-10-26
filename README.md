# HikeHK offline maps

Versioned regional map previews used by HikeHK. This public repository distributes map data and source notices; application source code is maintained separately.

## Download

[Map previews v1](https://github.com/takiihor/hikehk-maps/releases/tag/maps-v1) contains two PMTiles archives for each of six regions: Hong Kong Island, Kowloon and Lion Rock, Sai Kung, Northeast New Territories, West New Territories, and Lantau.

Each region has `<region>-base.pmtiles` and `<region>-terrain.pmtiles`. `RegionalPreviews-index.json` and `manifest.json` record the expected byte counts and SHA-256 digests. HikeHK verifies both before using a download. The combined map archives are 138,302,468 bytes. Keep the release tag and attachment contents fixed for this version.

## Sources and attribution

© OpenStreetMap contributors (ODbL 1.0); © OpenMapTiles; Made with Natural Earth; © Government of the Hong Kong Special Administrative Region, Lands Department. Complete source and rights notices, upstream licence text and recorded source evidence are attached to the release. The OSM-derived databases are distributed under ODbL 1.0; other source data retain their respective terms. This repository does not select a licence for the private application code.

The source OSM extract is dated 2026-10-09. Terrain uses approximately 5 m Hong Kong Principal Datum data; 0.1 m RGB encoding does not imply 0.1 m survey accuracy. The build rectangles overlap and are not official administrative or park boundaries.

These are dated, browse-only previews. They have not been field verified and do not establish current access, map accuracy or safety. No government endorsement is claimed.
