# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Possibility to disable console warnings ([Issue#9])
- `undefined` value not handled ([Issue#11])

## [1.2.0]

### Changed

- Changed the Cookie lib to be able to set `SameSite` ([Issue#7], [PR#8])
- (DEV) Update the dependencies

## [1.1.1]

### Fixed

- SyntaxError when the value can't be parsed as a JSON ([Issue#3])

### Changed

- Update (dev) dependencies version

## [1.1.0]

### Added

- Add external change listener for SessionStorage and LocalStorage
- Add documentation
- Add IndexedDB Storage

## [1.0.2]

### Fixed

- Add protection on global `document` variable

## [1.0.1]

### Added

- Add `noop` Storage that do nothing

### Fixed

- Add protection on global `window` variable

## [1.0.0]

First version

[Unreleased]: https://github.com/MacFJA/svelte-persistent-store/compare/1.2.0...HEAD
[1.2.0]: https://github.com/MacFJA/svelte-persistent-store/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/MacFJA/svelte-persistent-store/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/MacFJA/svelte-persistent-store/compare/1.0.2...1.1.0
[1.0.2]: https://github.com/MacFJA/svelte-persistent-store/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/MacFJA/svelte-persistent-store/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/MacFJA/svelte-persistent-store/releases/tag/1.0.0

[Issue#3]: https://github.com/MacFJA/svelte-persistent-store/issues/3
[Issue#7]: https://github.com/MacFJA/svelte-persistent-store/issues/7
[Issue#9]: https://github.com/MacFJA/svelte-persistent-store/issues/9
[Issue#11]: https://github.com/MacFJA/svelte-persistent-store/issues/11
[PR#8]: https://github.com/MacFJA/svelte-persistent-store/pull/8