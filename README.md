# Cook International Casino Portal v10.5.0 Alpha

Custom domain: `portal.cook-international.com`

The portal is self-contained and uses the existing Apps Script endpoint. It expects backend version `v10.5.0 Alpha`.

## Credential behavior

The backend stores plaintext passwords in the existing Google Sheet credential columns. No Google Sheet columns are renamed, removed, reordered, or added by this portal package.

## Data behavior

After login, the portal:

- reads existing sheet headers in their existing order;
- displays current row counts in each tab;
- calculates the House Dashboard directly from current Players, Game Ledger, Purchases, KYC, and Admin Log rows;
- does not require a Reports row before showing data.

Upload the contents of this directory to the root of the GitHub repository serving `portal.cook-international.com`.
