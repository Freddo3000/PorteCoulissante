# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.3] - 2014-02-23
### Added
- Undocumented additionalWallMaterials option

### Changed
- Updated copyright statements

## [1.4.2] - 2014-02-21
### Changed
- Updated dependencies

## [1.4.1] - 2012-12-22
### Added
- Support for versions 1.4.5 and later of bukkit API
  (The mapping of cardinal directions to coordinate axes was rotated)

## [1.4.0] - 2012-12-15
### Added
- Support for custom sounds through SpoutPlugin (http://www.spout.org/)
- Support for new Minecraft 1.4 block types

### Deprecated
- Support for Java 5

## [1.3.0] - 2012-05-08
### Added
- A default config.yml file is created whenever there isn't one.
- New options to restrict power blocks (the frame blocks through which the redstone power is delivered)
- New option to disallow "floating" portcullises

## [1.2.9] - 2012-05-20
### Added
- Support new solid blocks for frame (end stone, etc.)

### Fixed
- Ignore redstone current through sign posts and wall signs

## [1.2.8] - 2012-03-07
### Changed
- Updated copyright

### Fixed
- Destroy portculisses at the actual map height, not at hardcoded level of 128

## [1.2.7] - 2012-02-28
### Changed
- Migrated to new event handling and configuration mechanism
- Less severe warning when using non-standard settings

## [1.2.6] - 2011-10-21
### Added
- Added copyright information

### Changed
- Also enable physics when exploding portcullis.

### Fixed
- Don't break when someone changes the blocktype of an existing portcullis.

## [1.2.5] - 2011-10-03
### Fixed
- Do physics updates when hoisting or dropping portcullis (again).

## [1.2.4] - 2011-09-24
### Changed
- Use constants containing block IDs instead of *.getId()

## [1.2.2] - Unknown Changes

## [1.2.0] - Unknown
### Changed
- Entities and items on top of the portcullis are now moved upwards when the portcullis is hoisted. It will crush you against the ceiling!

## [1.1.0] - Unknown
### Changed
- Portcullises are now checked for integrity. That is, they must be rectangular, and have no holes or bits sticking out, otherwise they won't move!
- The portcullis will now go through water and lava.
- It starts moving a little more quickly (the speed once it's moving is unchanged).

## [1.0.3] - Unknown
### Changed
- Make the code more robust in an effort to work around some mysterious bugs.

## [1.0.2] - Unknown
### Fixed
- Make multiple portcullises work correctly.

## [1.0.1] - Unknown
### Fixed
- Fixed a bug with portcullises that extended to the west.

## [1.0.0] - Unknown
### Added
- Initial Release
