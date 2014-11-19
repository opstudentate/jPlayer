# Change Log
All notable changes to this project will be documented in this file.

## 2.8.2 - 2014-11-19 date TBD
### Added
- Package Fix: The un-minified source is now also added to the `dist` folder.
- New Feature: Merged Pull Request to add [commonJS support](https://github.com/happyworm/jPlayer/pull/257) by [nervo](https://github.com/nervo).
- Added CHANGELOG.md and gave details back to 2.7.1
- Added MIGRATION.md as placeholder for migration details.

### Changed
- Package Fix: Renamed the built folder to `dist`, which is more appropriate than the previous naming of `js`.

### Removed
- The old `js` build folder.

## 2.8.1 - 2014-11-13
### Added
- Skin Fix: Added the CSS3 rule to disable the default Firefox focus highlighting. Fixed both the Blue Monday and Pink Flag skins.
- Bug Fix: Fixed the media title being displayed in iOS Control Center when there is no GUI title element.

## 2.8.0 - 2014-11-11
### Added
- ARIA Feature: The `autoBlur` option will now either `blur()` or `focus()`. This helps maintain cross-browser behaviour when a user clicks on a GUI button.
- New Feature: Added the `noVolume` state class for when the volume controls are being hidden due to the `noVolume option`. This helps GUI design by enabling a CSS rule to hide the volume controls.
- jPlayer Repository Refactor: Added all download content to the repository and added a grunt build system. The example demos work within the repository, and use the built (minified) jPlayer files.

## Changed
- Refactor: Renamed the SWF file from `Jplayer.swf` to `jquery.jplayer.swf`
- Refactor: The Flash ``jquery.jplayer.swf` file is now compiled using the Flex compiler in the `grunt-mxmlc` node.js module.

## Removed
- Refactor: Refactored the Flash ActionScript, removing the `TraceOut` class from the `Jplayer.as` code and the `happyworm` package.

## 2.7.1 - 2014-09-19
### Added
- Bug Fix: Fixed the legacy Android fix to work with latest Android. This moved the android fix code to the `loadeddata` event from the `progress` event.

## 2.7.0 - 2014-09-01