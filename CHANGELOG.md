# Change Log

## [Unreleased]
### Added
- Reading of collision shells
- Reading and Writing of LOD nodes
- Reading and Writing of per-object Damage Arguments
- Reading of LightNodes (means A10-C cockpit now works)
- Writing of Connectors

### Changed
- (Internal) Streamlining, meaning it's easier to add features to the importer
- Switched to new documentation; see https://ndevenish.github.io/Blender_ioEDM
- Imported Connectors should now have more sensible sizes

## [0.2.0] - 2016-12-14
### Added
- Writing of Collision shells
- Reading of the new v10 .EDM files

### Changed
- Fixed UV writing to be normally in the range 0-1
- Convert specularity better; not everything should always be super shiny now

## [0.1.0] - 2016-12-07
### Added
- Initial release

[Unreleased]: https://github.com/ndevenish/Blender_ioEDM/compare/v0.2.0...master
[0.2.0]: https://github.com/ndevenish/Blender_ioEDM/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/ndevenish/Blender_ioEDM/releases/tag/v0.1.0