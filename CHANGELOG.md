# Changelog — RecordWeb Concept (RWC)

All notable changes to this concept are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/).

---

## [0.0.2] – 2026-08-04

Editorial alignment between RWC and RWP:

- RWC §11.3: aligned metadata field names to camelCase (`accessPolicy`, `deletionRegime`)
- RWP §9.5: corrected pseudocode return types and restored missing bracket
- RWP §14.1: removed duplicate chapter reference in Level 2 conformance list
- Both documents: added explicit `Version: 0.0.2` in Bikeshed metadata

## [0.0.1] — 2026-06-26

### Added
- Initial Editor's Draft of the RecordWeb Concept (RWC)
- Full content from published baseline (Zenodo DOI: 10.5281/zenodo.20475343)
- Bikeshed metadata header with CG-DRAFT status
- Structured sections with HTML anchors for all chapters
- Defined terms using Bikeshed `<dfn>` markup: Record, Case, Version graph, Finalisation, Branch, Merkle root, DID, Payload, Metadata, Owner, State transition, Directed Acyclic Graph (DAG), draft, finalized
- Normative reference to RWP (RecordWeb Protocol)
- Informative references: ISO 15489, ISO 14721, PROV-O, DID Core, Solid, Nanopublications, eCH-0164, Git, Hyperledger, Linked Data, Records Continuum
- HTML data tables replacing LaTeX longtable environments
- GitHub Actions workflow (w3c/spec-prod) for automatic build and GitHub Pages deployment
