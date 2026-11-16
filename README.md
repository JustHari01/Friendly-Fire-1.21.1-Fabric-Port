# Friendly Fire (UNOFFICIAL) — Fabric 1.21.1

An independent Fabric port of Friendly Fire by Darkhax for Minecraft 1.21.1. The port keeps the original protection rules and configuration while updating the code and data resources for this Minecraft version.

## Features

- Prevents players from accidentally hurting their own pets.
- Prevents pets with the same owner from hurting each other.
- Protects allied team members, according to the mod configuration.
- Protects baby non-hostile animals.
- Supports item and entity tags for bypasses and extra protection rules.
- Can reflect blocked damage and show an action-bar warning.
- Sneaking remains a temporary bypass.

## Requirements

- Minecraft 1.21.1
- Fabric Loader
- Fabric API
- Bookshelf 21.1.0 or newer for Minecraft 1.21.1
- Java 21

## Build

Run gradlew.bat remapJar on Windows. The release JAR is written to build/libs.

## Configuration

The settings are stored in config/friendlyfire.json. The options control pet protection, baby-animal protection, damage reflection, warnings, team protection, and whether team rules are respected.

## Attribution and license

The original Friendly Fire project and code were created by Darkhax: [CurseForge](https://www.curseforge.com/minecraft/mc-mods/friendly-fire) · [Modrinth](https://modrinth.com/mod/friendly-fire) · [source repository](https://github.com/Darkhax-Minecraft/Friendly-Fire). This port is based on upstream commit d388e48e8a566fb036a725ec12065c589278669a from the 1.20.4 branch.

This port is not affiliated with or endorsed by Darkhax. The source and modifications are distributed under the GNU Lesser General Public License, version 2.1 only. See [LICENSE](LICENSE).

AI assistance was used for the 1.21.1 compatibility and porting work.
