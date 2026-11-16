# Porting notes

This repository is an independent Fabric 1.21.1 port of the source at [Darkhax-Minecraft/Friendly-Fire](https://github.com/Darkhax-Minecraft/Friendly-Fire), based on upstream commit d388e48e8a566fb036a725ec12065c589278669a from branch 1.20.4.

## Compatibility changes

- Updated FriendlyFireCommon.java to use the 1.21.1 ResourceLocation factory and Bookshelf 21.1 platform service API.
- Updated the Mixin compatibility level and Fabric metadata for Minecraft 1.21.1 and Java 21.
- Renamed data tag directories to the singular paths used by Minecraft 1.21.1; tag contents were retained.
- Updated the resource-pack format number.
- Kept the original configuration, mixin behavior, translations, tag contents, and 200×200 in-game icon.
- Added branding/friendly-fire-logo-400x400.png as a pixel-exact 2× scale of the original icon for CurseForge's minimum project-logo dimensions.

No gameplay rules were intentionally changed. The project has been compile/remap-built; no in-game runtime test is claimed.

## License

The project and modifications are distributed under LGPL-2.1-only. See LICENSE. The modified Java file carries an in-file notice with the modification date.
