# Zoomies wallet test environment

Separate static hosting for TON Connect metadata used by the local Zoomies development game. This repository must not be connected to Lovable or deployed as the live game.

## Public files

- `index.html`: explanatory landing page; no JavaScript or wallet signing.
- `tonconnect-manifest.json`: test application identity.
- `zoomies-icon.png`: existing public Zoomies icon.
- `test-gram.json`: metadata for the non-monetary zGRAM-TEST token (9 decimals).
- `.nojekyll`: serve the static files without Jekyll processing.

Publish GitHub Pages from `main`, repository root. Expected base URL: `https://g4mb1tnoone.github.io/zoomies-wallet-testnet/`.

These files do not deploy a token, accept deposits, award credits, or enable withdrawals. Token deployment and wallet proofs require separate checks and user approval in the wallet. Never add private configuration, recovery phrases, signing keys, a database, or game source here.
