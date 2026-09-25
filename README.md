# ReBagged Catalogue

Open, machine-readable publication repository for verified ReBagged set and bag data.

This repository is the public output of the ReBagged publishing pipeline. It contains catalogue metadata plus portable BSX bag-data files. Scanning history, model internals, review state, and the ReBagged server/admin source remain private.

## Published layout

- `catalogue.json` — set metadata and pointers to published BSX data.
- `sets/<set-number>/r<revision>.bsx` — immutable published revisions.
- `sets/<set-number>/latest.bsx` — current published revision for consumers.

Published BSX revisions are intended to be usable by ReBagged clients and third-party tools without requiring access to the private ReBagged application repository.

This repository has been reset from the legacy database-based catalogue format. New catalogue content should be produced by the current ReBagged publish pipeline.
