# Changelog — RecordWeb Concept (RWC)

All notable changes to this concept are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
Versioning follows [Semantic Versioning](https://semver.org/).

---

## [0.0.3] – 2026-08-06

Editorial: standards and national mappings

This version introduces editorial and scoping clarifications around standards referenced by RecordWeb:

- Clarified the description of the classical lifecycle (Section 4.3) as anchored in ISO 15489 and other national standards (e.g. Switzerland eCH-0164), instead of singling out Switzerland alone.
- Refined the discussion of ISO 15489: the section now focuses on ISO as the international foundation for RecordWeb’s requirements, with national lifecycle frameworks (such as eCH-0164) explicitly treated as jurisdiction-specific mappings defined by their respective owners.
- Removed git from the “Related Concepts” section; git is referenced only as an implementation analogy for DAGs, not as a records or archival standard.
- Updated Annex B to state that RecordWeb directly maintains only international standards (ISO, W3C, IETF, etc.) and core conceptual frameworks. National or sectoral standards MAY be listed as non-normative mappings, with relationship text supplied by the standard owners.
- Marked the relationship text for eCH-0164 in Annex B as “TBD by eCH”, making explicit that RecordWeb does not define the official mapping for this national standard. Others as "TBD by RecordWeb CG".
- Removed explicit chapter "Introduction" as the info is in the doc by W3C-Template (Status of this document).

These changes do not introduce new normative requirements. They clarify RecordWeb’s positioning: grounded in international standards, open to national mappings without structural dependency.

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
