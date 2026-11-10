# Delivery intake — 3592-k7q2

<!-- intake-fixture:3592-k7q2:v1 -->

This repository is the shared home of the intake programme. Each contributor
works on their own branch under `contrib/<handle>` and delivers bundles in
`intake/<handle>/<bundle>/`.

## Where things live

- `intake/README.md` — the bundle layout every delivery must follow.
- `intake/template/bundle-skeleton/` — canonical bundle skeleton.
- `intake/portal/scorecard.html` — published intake scorecard (system of record).
- `intake/portal/data.json` — nightly convenience export produced by the
  reporting bot; it is not the system of record.

## Published scorecard

https://raw.githack.com/komal74784391-netizen/delivery-intake-3592-k7q2/main/intake/portal/scorecard.html

Open that link in a browser; the scorecard register is rendered by the portal
itself, and the acknowledgement gate must be completed before the sections can
be opened.

## Contributors

Delivery branches follow `contrib/<handle>`. The intake coordinator inspects the
newest delivery on each branch; older deliveries remain in the register as
archived records.
