# Bundle layout

A **bundle** is a folder at `intake/<contributor>/<bundle>/`. It must directly
contain both of these sub-folders:

- `spec/` — the study specification and acceptance notes.
- `evidence/` — run logs and supporting artefacts.

Optional `assets/` may also appear inside a bundle.

A folder that sits directly in `intake/<contributor>/` and only contains files
(as opposed to having its own `spec/` and `evidence/` sub-folders) is **not** a
bundle. The names `spec`, `evidence` and `assets` are reserved for the internal
sub-folders and are never bundle names.

Use `intake/template/bundle-skeleton/` as the canonical shape. Every genuine
bundle in every branch follows this shape.
