# Security

To report a vulnerability in any Thurin Labs project (the PGPRegistry contract, identity-kit,
the Thurin CLI, thurin.id, and the rest), email hello@thurin.id. Please don't open a public issue.

## Encrypted reports

Encrypt sensitive reports to the Thurin Labs PGP key:

Fingerprint: `08B9 374F DFBE C67E FFA2  4E66 9D3D 86E3 5361 EF7B`
Key: https://thurin.id/pgp/08B9374FDFBEC67EFFA24E669D3D86E35361EF7B.asc

The key is claimed on Ethereum by `0x539C7e1E454296Dc150B95a0acCC05bCa3b33538` (thurinlabs.eth).
Before you send, check that the claim is current and made by that address:
https://thurin.id/pgp/08B9374FDFBEC67EFFA24E669D3D86E35361EF7B

The registry contract is immutable and has no admin, so a flaw in it can't be patched in place.
Reports are still wanted: they shape the next version and what the tools warn about.
