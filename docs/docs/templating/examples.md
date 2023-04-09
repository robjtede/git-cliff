# Examples

Examples are based on the following Git history:

```log
* df6aef4 (HEAD -> master) feat(cache): use cache while fetching pages
* a9d4050 feat(config): support multiple file formats
* 06412ac (tag: v1.0.1) chore(release): add release script
* e4fd3cf refactor(parser): expose string functions
* ad27b43 (tag: v1.0.0) docs(example)!: add tested usage example
* 9add0d4 fix(args): rename help argument due to conflict
* a140cef feat(parser): add ability to parse arrays
* 81fbc63 docs(project): add README.md
* a78bc36 Initial commit
```

Test repository can be found [here](https://github.com/orhun/git-cliff-readme-example).

See [examples](https://github.com/orhun/git-cliff/tree/main/examples) directory for example configuration files.

If you have a custom configuration file that you are using for your project(s), consider sharing it with us by [submitting a pull request](https://github.com/orhun/git-cliff/blob/main/CONTRIBUTING.md)!

#### [Basic](https://github.com/orhun/git-cliff/tree/main/config/cliff.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- Add release script

### Refactor

- Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict

### Documentation

- Add README.md
- Add tested usage example

### Features

- Add ability to parse arrays

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- Add release script

### Refactor

- Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict

### Documentation

- Add README.md
- Add tested usage example

### Features

- Add ability to parse arrays

<!-- generated by git-cliff -->

</details>

#### [Minimal](https://github.com/orhun/git-cliff/tree/main/examples/minimal.toml)

<details>
  <summary>Raw Output</summary>

```
## [unreleased]
### Feat
- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18
### Chore
- Add release script

### Refactor
- Expose string functions

## [1.0.0] - 2021-07-18
### Docs
- Add README.md
- [**breaking**] Add tested usage example

### Feat
- Add ability to parse arrays

### Fix
- Rename help argument due to conflict
```

</details>

<details>
  <summary>Rendered Output</summary>

## [unreleased]

### Feat

- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Chore

- Add release script

### Refactor

- Expose string functions

## [1.0.0] - 2021-07-18

### Docs

- Add README.md
- [**breaking**] Add tested usage example

### Feat

- Add ability to parse arrays

### Fix

- Rename help argument due to conflict

</details>

#### [Limited Commits](https://github.com/orhun/git-cliff/tree/main/examples/limitedcommits.toml)

<details>
  <summary>Raw Output</summary>

```
## [unreleased]
### Feat
- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18
### Chore
- Add release script
```

</details>

<details>
  <summary>Rendered Output</summary>

## [unreleased]

### Feat

- Support multiple file formats
- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Chore

- Add release script

</details>

#### [Detailed](https://github.com/orhun/git-cliff/tree/main/examples/detailed.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats ([a9d4050](a9d4050212a18f6b3bd76e2e41fbb9045d268b80))
- Use cache while fetching pages ([df6aef4](df6aef41292f3ffe5887754232e6ea7831c50ba5))

## [1.0.1] - 2021-07-18

[ad27b43](ad27b43e8032671afb4809a1a3ecf12f45c60e0e)...[06412ac](06412ac1dd4071006c465dde6597a21d4367a158)

### Miscellaneous Tasks

- Add release script ([06412ac](06412ac1dd4071006c465dde6597a21d4367a158))

### Refactor

- Expose string functions ([e4fd3cf](e4fd3cf8e2e6f49c0b57f66416e886c37cbb3715))

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict ([9add0d4](9add0d4616dc95a6ea8b01d5e4d233876b6e5e00))

### Documentation

- Add README.md ([81fbc63](81fbc6365484abf0b4f4b05d384175763ad8db44))
- Add tested usage example ([ad27b43](ad27b43e8032671afb4809a1a3ecf12f45c60e0e))

### Features

- Add ability to parse arrays ([a140cef](a140cef0405e0bcbfb5de44ff59e091527d91b38))

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats ([a9d4050](a9d4050212a18f6b3bd76e2e41fbb9045d268b80))
- Use cache while fetching pages ([df6aef4](df6aef41292f3ffe5887754232e6ea7831c50ba5))

## [1.0.1] - 2021-07-18

[ad27b43](ad27b43e8032671afb4809a1a3ecf12f45c60e0e)...[06412ac](06412ac1dd4071006c465dde6597a21d4367a158)

### Miscellaneous Tasks

- Add release script ([06412ac](06412ac1dd4071006c465dde6597a21d4367a158))

### Refactor

- Expose string functions ([e4fd3cf](e4fd3cf8e2e6f49c0b57f66416e886c37cbb3715))

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict ([9add0d4](9add0d4616dc95a6ea8b01d5e4d233876b6e5e00))

### Documentation

- Add README.md ([81fbc63](81fbc6365484abf0b4f4b05d384175763ad8db44))
- Add tested usage example ([ad27b43](ad27b43e8032671afb4809a1a3ecf12f45c60e0e))

### Features

- Add ability to parse arrays ([a140cef](a140cef0405e0bcbfb5de44ff59e091527d91b38))

<!-- generated by git-cliff -->

</details>

#### [Scoped](https://github.com/orhun/git-cliff/tree/main/examples/scoped.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

#### Cache

- Use cache while fetching pages

#### Config

- Support multiple file formats

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

#### Release

- Add release script

### Refactor

#### Parser

- Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

#### Args

- Rename help argument due to conflict

### Documentation

#### Example

- Add tested usage example

#### Project

- Add README.md

### Features

#### Parser

- Add ability to parse arrays

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

#### Cache

- Use cache while fetching pages

#### Config

- Support multiple file formats

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

#### Release

- Add release script

### Refactor

#### Parser

- Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

#### Args

- Rename help argument due to conflict

### Documentation

#### Example

- Add tested usage example

#### Project

- Add README.md

### Features

#### Parser

- Add ability to parse arrays

<!-- generated by git-cliff -->

</details>

#### [Scoped (Sorted)](https://github.com/orhun/git-cliff/tree/main/examples/scopesorted.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- *(cache)* Use cache while fetching pages
- *(config)* Support multiple file formats

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- *(release)* Add release script

### Refactor

- *(parser)* Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

- *(args)* Rename help argument due to conflict

### Documentation

- *(example)* Add tested usage example
  - **BREAKING**: add tested usage example
- *(project)* Add README.md

### Features

- *(parser)* Add ability to parse arrays

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- _(cache)_ Use cache while fetching pages
- _(config)_ Support multiple file formats

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- _(release)_ Add release script

### Refactor

- _(parser)_ Expose string functions

## [1.0.0] - 2021-07-18

### Bug Fixes

- _(args)_ Rename help argument due to conflict

### Documentation

- _(example)_ Add tested usage example
  - **BREAKING**: add tested usage example
- _(project)_ Add README.md

### Features

- _(parser)_ Add ability to parse arrays

<!-- generated by git-cliff -->

</details>

#### [Keep a Changelog](https://github.com/orhun/git-cliff/tree/main/examples/keepachangelog.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Support multiple file formats

### Changed

- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Added

- Add release script

### Changed

- Expose string functions

## [1.0.0] - 2021-07-18

### Added

- Add README.md
- Add ability to parse arrays
- Add tested usage example

### Fixed

- Rename help argument due to conflict

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Support multiple file formats

### Changed

- Use cache while fetching pages

## [1.0.1] - 2021-07-18

### Added

- Add release script

### Changed

- Expose string functions

## [1.0.0] - 2021-07-18

### Added

- Add README.md
- Add ability to parse arrays
- Add tested usage example

### Fixed

- Rename help argument due to conflict

<!-- generated by git-cliff -->

</details>

#### [Unconventional](https://github.com/orhun/git-cliff/tree/main/examples/unconventional.toml)

<details>
  <summary>Raw Output</summary>

```
# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats ✔️
- Use cache while fetching pages ✔️

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- Add release script ✔️

### Refactor

- Expose string functions ✔️

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict ✔️

### Documentation

- Add README.md ✔️
- Add tested usage example ✔️

### Features

- Add ability to parse arrays ✔️

### Other (unconventional)

- Initial commit ❌

<!-- generated by git-cliff -->
```

</details>

<details>
  <summary>Rendered Output</summary>

# Changelog

All notable changes to this project will be documented in this file.

## [unreleased]

### Features

- Support multiple file formats ✔️
- Use cache while fetching pages ✔️

## [1.0.1] - 2021-07-18

### Miscellaneous Tasks

- Add release script ✔️

### Refactor

- Expose string functions ✔️

## [1.0.0] - 2021-07-18

### Bug Fixes

- Rename help argument due to conflict ✔️

### Documentation

- Add README.md ✔️
- Add tested usage example ✔️

### Features

- Add ability to parse arrays ✔️

### Other (unconventional)

- Initial commit ❌

<!-- generated by git-cliff -->

</details>