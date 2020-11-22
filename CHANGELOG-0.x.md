# Release Notes

## [Unreleased](https://github.com/ishanvyas22/asset-mix/compare/0.6.4...cake3)

## [0.6.4 (2020-11-22)](https://github.com/ishanvyas22/asset-mix/compare/0.6.3...0.6.4)

### Changed
- Badges to use GitHub Actions workflow status ([a43f7dc](https://github.com/ishanvyas22/asset-mix/commit/a43f7dce6ccead62a151f3c8afa5dd5f14e9bffb))

## [0.6.3 (2020-11-15)](https://github.com/ishanvyas22/asset-mix/compare/0.6.2...0.6.3)

### Changed
- Move CI to github actions

## [0.6.2 (2020-08-30)](https://github.com/ishanvyas22/asset-mix/compare/0.6.1...0.6.2)

### Fixed
- Fix CS in `app.js` file for inertia-vue scaffolding ([6e3a7c0](https://github.com/ishanvyas22/asset-mix/commit/6e3a7c042115f0119e71be0867cc50020182b088))
- Fix indentation in `webpack.mix.js` file for inertia-vue scaffolding ([594a428](https://github.com/ishanvyas22/asset-mix/commit/594a428239e7169565c8de1d364ad872ed7b4fa4))

### Removed
- Remove route mixin for inertia-vue scaffolding ([8165af9](https://github.com/ishanvyas22/asset-mix/commit/8165af98e2c3bb174482e0d53267465f07db8b0a))

## [0.6.1 (2020-08-23)](https://github.com/ishanvyas22/asset-mix/compare/0.6.0...0.6.1)

### Fixed
- Invalid directory name in webpack.mix.js file for `inertia-vue` scaffolding ([82f0a49](https://github.com/ishanvyas22/asset-mix/commit/82f0a49beb71853217d9e070cb1cddc55cec209a))

## [0.6.0 (2020-08-22)](https://github.com/ishanvyas22/asset-mix/compare/0.5.1...0.6.0)

### Added
- Added `inertia-vue` scaffolding ([#20](https://github.com/ishanvyas22/asset-mix/pull/20))
- Added `check` script alias in composer.json file to run all the checks together ([03fe3fe](https://github.com/ishanvyas22/asset-mix/commit/03fe3feb94f6fb2032d4694a7d9d29db477ba199))

### Changed
- Changed js indent size from 2 to 4 in `.editorconfig` file ([3f2432f](https://github.com/ishanvyas22/asset-mix/commit/3f2432fe6b2e5fde79058303249255278898125e))
- Changed vue indent size from 2 to 4 in `.editorconfig` file ([3aa86be](https://github.com/ishanvyas22/asset-mix/commit/3aa86be1405a55874a1e202480f2d748007c87e5))

## [0.5.1 (2020-08-08)](https://github.com/ishanvyas22/asset-mix/compare/0.5.0...0.5.1)

### Added
- Add "Support the development" section in README.md

### Changed
- Change installation version to ^0.5 from ^0.4 in README.md
- Move 0.x version up in version map table in README.md

## [0.5.0 (2020-08-08)](https://github.com/ishanvyas22/asset-mix/compare/0.4.3...0.5.0)

### Added
- Ability to generate scaffoldings for Bootstrap / Vue / React for CakePHP 3.x (#3)

## [0.4.3 (2020-07-26)](https://github.com/ishanvyas22/asset-mix/compare/0.4.2...0.4.3)

### Fixed
- Wrong directory name in webpack.mix.js file for custom directory ([#14](https://github.com/ishanvyas22/asset-mix/issues/14))

## [0.4.2 (2020-07-23)](https://github.com/ishanvyas22/asset-mix/compare/0.4.1...0.4.2)

### Added
-  Added cs-fix alias to auto fix coding standard ([77ef0f2](https://github.com/ishanvyas22/asset-mix/commit/77ef0f2dab115abaf051087b020fe5966042f52d))
-  Added version map in `README.md` file to notify that `cake3` branch is supported for CakePHP 3.5+ ([b184e00](https://github.com/ishanvyas22/asset-mix/commit/b184e000cc57baa7b5527845cbe4268cef1a7ecb))
-  Update travis config to setup CI for cake3 branch ([cfa1c9f](https://github.com/ishanvyas22/asset-mix/commit/cfa1c9f926c62b4aaec813295dca0fda7048cff1))

## [0.4.1 (2020-07-23)](https://github.com/ishanvyas22/asset-mix/compare/0.4.0...0.4.1)

### Added
- Add phpstan dependency ([#10](https://github.com/ishanvyas22/asset-mix/pull/10))
- Add CHANGLOG.md file ([#9](https://github.com/ishanvyas22/asset-mix/issues/9))

### Fixed
- Errors from phpstan ([#10](https://github.com/ishanvyas22/asset-mix/pull/10))

### Changed
- Remove check for PHP 7.0 in travis ci ([#10](https://github.com/ishanvyas22/asset-mix/pull/10))
- Add check for PHP 7.3 in travis ci ([#10](https://github.com/ishanvyas22/asset-mix/pull/10))
- Optimize travis checks by removing unit test command for each build ([#10](https://github.com/ishanvyas22/asset-mix/pull/10))
- Rename `CHANGLOG.md` to `CHANGELOG-0.x.md` file ([1248653](https://github.com/ishanvyas22/asset-mix/commit/1248653fb1e72980af11ac9e4e654fb8d8c13073))
-  Ignore tool specific and OS generated files from git ([2eb7671](https://github.com/ishanvyas22/asset-mix/commit/2eb7671a1d8918ae1359370d335aa3a6eb933ec3))

## [0.4.0 (2019-11-09)](https://github.com/ishanvyas22/asset-mix/compare/0.3.2...0.4.0)

### Added
- Add `asset_mix generate` command ([#7](https://github.com/ishanvyas22/asset-mix/pull/7))
- Add Generate command section in README.md file ([86a0de63](https://github.com/ishanvyas22/asset-mix/commit/9ac452222d69a4ab684d43fcff5b85f286a0de63))
- Add step to compile assets in README.md file ([4c7724ca](https://github.com/ishanvyas22/asset-mix/commit/5e7b99aec6be46f4b27395bf37c480624c7724ca))

### Changed
- Drop dependency of symfony/filesystem, add dependency of league/flysystem ([#8](https://github.com/ishanvyas22/asset-mix/pull/8))

## [0.3.2 (2019-11-09)](https://github.com/ishanvyas22/asset-mix/compare/0.3.1...0.3.2)

### Added
- Added poser badges ([b1888ca4](https://github.com/ishanvyas22/asset-mix/commit/53e34fe1cd3a8909f64464679662da5bb1888ca4), [baa4064b](https://github.com/ishanvyas22/asset-mix/commit/6473779254872498f5355eea38966d7abaa4064b))
- Issue templates ([187db244](https://github.com/ishanvyas22/asset-mix/commit/60ef6d736c946e754785fab7253a2b93187db244))
- Added cakephp code sniffer package ([9ca452c3](https://github.com/ishanvyas22/asset-mix/commit/76340bbf5b6b3e5b3ff36b6f229984439ca452c3))
- Added travis.yml config

## [0.3.1 (2019-11-01)](https://github.com/ishanvyas22/asset-mix/compare/0.3.0...0.3.1)

### Added
- Tests to check `<style>` tag with and without versioning enabled ([22f8a1fa](https://github.com/ishanvyas22/asset-mix/pull/5/commits/191b57bd9bcfca791eea43ae9934268b22f8a1fa))
- Tests to check `<script>` tag with and without versioning enabled ([22f8a1fa](https://github.com/ishanvyas22/asset-mix/pull/5/commits/191b57bd9bcfca791eea43ae9934268b22f8a1fa))

### Changed
- Public path change to `WWW_ROOT` constant ([81882513](https://github.com/ishanvyas22/asset-mix/pull/5/commits/1a084d2dcbc311ce1d36a438d458dafe81882513))
- `composer.json` changes ([ff9bcc76](https://github.com/ishanvyas22/asset-mix/pull/5/commits/ed7ab236a8aa6ea0a9f87818f70d5858ff9bcc76))

## [0.3.0 (2019-10-31)](https://github.com/ishanvyas22/asset-mix/compare/0.2.0...0.3.0)

### Added
- `<script>` tag will now have the `defer` attribute by default ([#4](https://github.com/ishanvyas22/asset-mix/pull/4))
- `env()` function used instead of `$_SERVER` global variable ([#4](https://github.com/ishanvyas22/asset-mix/pull/4))
- `functions.php` loaded directly from composer instead of bootstrap file ([#4](https://github.com/ishanvyas22/asset-mix/pull/4))

### Changed
- Plugin name, namespace changed to AssetMix from Mix ([#4](https://github.com/ishanvyas22/asset-mix/pull/4))

## [0.2.0 (2019-10-28)](https://github.com/ishanvyas22/asset-mix/compare/0.1.0...0.2.0)

### Added
- Installation steps into README.md file ([#1](https://github.com/ishanvyas22/asset-mix/pull/1))
- Usage section into README.md file ([#1](https://github.com/ishanvyas22/asset-mix/pull/1))
- Reference section into README.md file ([#1](https://github.com/ishanvyas22/asset-mix/pull/1))
- Issues section into README.md file ([#1](https://github.com/ishanvyas22/asset-mix/pull/1))

## 0.1.0 (2019-10-26)

**Initial release.**

### Added
- Helper function `css()` to call build css files from `mix-manifest.json` file.
- Helper function `script()` to call build js files from `mix-manifest.json` file.
- Supports versioning through `version()` function in `webpack.mix.js` file.