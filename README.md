# calemera-data

Data file of the themed calendars (holidays, religious feasts, sports fixtures) used by the Calèmera iOS app.

- `calendars.json`: the calendars, with `format`, `minimumAppVersion`, `version` and `generated`.
- `calendars.json.sig`: Ed25519 signature (base64) of the exact bytes of `calendars.json`. The app accepts the file only if the signature matches the public key built into it.

Published automatically; please do not edit by hand. Only fixtures and dates confirmed by official sources are included.
