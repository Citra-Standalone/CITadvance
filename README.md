# CITadvance
Magisk module for Tricky Store and PIF Fingerprint management. Easier to customize your setup for Tricky Store and PIF with CITadvance ( not limited to PIF Fork ). This module is made for advance user. If you dont know anything about what is going on with this module, **DO NOT USE THIS MODULE!** Find an alternative.

Some explaination about what this module do :
- Auto generate PIF device fingerprint.
- Auto add applist to `target.txt`
- Auto retrive key from Citra-standalone and generate `keybox.xml`.

## Instruction
To trigger it you must click **Action** button in magisk.

Do not install along/with TSupport. ( May have conflict )

You can create a new file with name `exclude.txt` in Internal Storage ( `/sdcard` or `/storage` ) to exclude a package name from added to `target.txt`.
<details>
<summary>About exclude.txt</summary>

When you add the package name inside `exclude.txt`, that package name will not add to `target.txt`. If you add the package name with "!" at the end of the package name, that package name will added to `target.txt` but without "!". For more information about this "!" function read [Tricky Store repository description](https://github.com/5ec1cff/TrickyStore).
</details>

## Requirements

- Magisk v27.0(27008)+
- Working Fizikal Key ( VOL+ VOL- POWER )
- PIF installed
- Tricky Store installed

## Acknowledgements

This repository incorporates code from the osm0sis project ([PlayIntegrityFork](https://github.com/osm0sis/PlayIntegrityFork)). I acknowledge that the original authors and contributors have created valuable work, and I encourage users to respect the licensing terms of the original project.


## Contact/Support
💬[Telegram](https://t.me/citraintegritytrick)
