# GDur4n66 LNbits Extensions

Extension manifest for LNbits extensions maintained by GDur4n66.

## Add this manifest to LNbits

Add the following URL under **Manage Server > Server > Extensions Manifests**:

```text
https://raw.githubusercontent.com/GDur4n66/lnbits-extensions/main/manifest.json
```

Then open **Manage Extensions > Add Remove Extensions** to install an available
release.

## Extensions

- `giftcard`: NFC Lightning gift-card issuing and management.

Each extension lives in its own repository. New extensions can be published by
adding another object to the `repos` array in `manifest.json` after their first
GitHub release is available.
