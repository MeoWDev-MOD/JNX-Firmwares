# JNX-Firmwares

🌐 **[Ler em português](README.md)**

Firmware repository of the **JNX MOD** app ([JNX-Updater](https://github.com/MeoWDev-MOD/JNX-Updater)).

## How it is organized

Each firmware is a [release](../../releases):

| Field | Pattern | Example |
|---|---|---|
| Tag | the firmware version | `1.2.0` |
| Title | `Firmware <version> ( AMS <version> )` | `Firmware 1.2.0 ( AMS 1.0.0 )` |
| Text | version, compatibility and SHA-256 of the zip | |
| File (asset) | `<version>.zip` | `1.2.0.zip` |

The app lists these releases in the **Firmwares** tab and extracts the zip contents to `/firmware` on the SD card.

## Repository rule

Publish here **only** firmware you created or that you have permission to distribute.
Do not publish third-party files without authorization, nor keys. If the rights holder asks for a file to be removed,
it will be removed.
