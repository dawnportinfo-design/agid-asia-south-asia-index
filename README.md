# AGID South Asia Index

AGID South Asia index for Asia country and territory repository coordination.

## Status

- Owner: `dawnportinfo-design`
- Repository: `agid-asia-south-asia-index`
- Stage: `wave-0-index`
- Data readiness: `index-ready`
- Privacy: no raw personal address, recipient, precise private coordinate, witness, or private-key material.

## Scope

This repository is an AGID coordination index. It stores repository pointers,
safe source policy, postal status, quality gates, conformance status, and special
region display policy for Asia address infrastructure.

It does not store private delivery addresses, recipient records, precise private
coordinates, witness material, private keys, large GIS extracts, map tiles, or
search indexes.

## Related Repositories

- `agid-country-in` - India (IN)
- `agid-country-pk` - Pakistan (PK)
- `agid-country-bd` - Bangladesh (BD)
- `agid-country-lk` - Sri Lanka (LK)
- `agid-country-af` - Afghanistan (AF)
- `agid-country-np` - Nepal (NP)
- `agid-country-bt` - Bhutan (BT)
- `agid-country-mv` - Maldives (MV)

## Data Boundary

GitHub may contain synthetic fixtures, rules, manifests, source notes, and
quality gate metadata. Large geography, hydrographic datasets, building
polygons, OSM/Overture extracts, and generated caches must stay in external
content-addressed packs.

## Special Region Policy

AGID repository placement is a technical address-data organization rule. It does
not imply sovereignty, recognition, or territorial ownership. Disputed or special
regions must carry explicit display policy before data publication.

## Validation

The repository includes JSON manifests and a lightweight GitHub Actions workflow
that validates JSON files. Public release content must pass AGID no-raw-address
review before data publication.
