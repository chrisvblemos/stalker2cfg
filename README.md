# Description

This is a dump of .cfg files from Stalker 2 game, extracted using FModel.

These are configuration files for damage, AI, quest logic, etc.
All `.cfg` files follow a custom data format that requires a parser written by GSC and to be released some time in the future for propert editing.
For now, all modding must be done with text editors unless someone writes a parser.

Structure follows a key-value data format, should be simple to understand.
When applicable, references to other files/objs are made using the `SIDs`.

There is also support for "struct" inheritance, done by `{refurl = ...; refkey = ....}`

## Main Branch
Contains the Steam version. 
**Current Version**: 1.1.2

## GDK Branch
Contains the Game Pass version.
**Current Version**: 1.0.1 _(missing SpawnActorPrototypes for now)_
