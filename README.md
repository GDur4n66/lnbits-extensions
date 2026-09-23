# GDur4n66 LNbits Extensions

Extension catalog maintained by GDur4n66.

## Install

Add this URL under **Manage Server > Server > Extensions Manifests**:

```text
https://raw.githubusercontent.com/GDur4n66/lnbits-extensions/main/manifest.json
```

Open **Manage Extensions > Add Remove Extensions** to install a listed version.

## Extensions

- **Denchi Card** (`denchi`): NFC Lightning card issuing, management and balance lookup. Requires Withdraw.

## Upgrade from Giftcard

Denchi Card 0.2.0 uses a new extension ID. Back up the database, disable Giftcard,
then install Denchi Card on the same LNbits instance. Its migration copies legacy
Profiles and card records while preserving existing wallets and Withdraw links.
Enable Denchi Card for each account; update bookmarks to `/denchi/`. NFC tags do
not need rewriting. Do not manage the same cards through both extensions.

See the [migration instructions](https://github.com/GDur4n66/denchi#upgrading-from-giftcard-010).

Each extension has its own repository. Add future releases to `extensions` with
an immutable archive URL and SHA-256 hash, or add a repository to `repos` when
publishing tagged GitHub releases. Denchi Card is hosted at `GDur4n66/denchi`; its extension ID is `denchi`.
