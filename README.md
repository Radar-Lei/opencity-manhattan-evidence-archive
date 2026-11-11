# OpenCity Manhattan — evidence-layer archive

Pinned acquisition-time extracts of the open-data layers used by the Manhattan
city model submitted to the IEEE Big Data Cup 2026 OpenCity Challenge
(Codabench 17882).

Several upstream publishers (NYC Open Data, MTA, NYSDOT, US Census) serve
continuously updated endpoints, so the bytes at the upstream URL drift after
the acquisition date and can no longer be re-hashed against the checksum the
submission declares. This archive preserves the exact bytes each layer carried
at acquisition time, so every checksum in the submission's
`connection_manifest.json` remains re-fetchable from a stable URL. The
upstream publisher URL, license and acquisition chain for every layer are
recorded in the manifest itself; this archive holds no material that is not
already carried, checksummed and licensed for redistribution inside the
submission.

Licenses: US Government works (public domain) for Census/LODES/TIGER/CBP;
NYC Open Data and NYC DOT terms; MTA developer data; NY State ITS public
access; transcribed factual capacity rates cited from the HCM 7th Edition.
