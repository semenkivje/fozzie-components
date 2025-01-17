# Changelog

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


v3.0.0
------------------------------
*October 5, 2021*

### Changed
- Background colour token in line with Icing Phase 2.


v2.0.0
------------------------------
*September 15, 2021*

- Return beta to master. Component has JETSansDigital font.

### Removed
- Normalise styles from the build. Note that now if consuming application doesn't have normalised (reset) styles, there may be some slight style differences after this update. If the consuming application uses fozzie, there shouldn't be any style differences as normalised styles should be added as part of the fozzie import.


v2.0.0-beta.0
------------------------------
*August 26, 2021*

### Updated
- New font JETSansDigital


v1.3.0
------------------------------
*May 25, 2021*

### Changed
- CSS variables to use pie design tokens instead of fozzie-colour-palette vars


v1.2.0
------------------------------
*February 9, 2021*

### Added
- Added `f-user-message.component.spec` tests
- Added accessibility tests


v1.1.0
------------------------------
*January 29, 2021*

### Added
- Added the component to storybook

### Changed
- Update service to use new values as the contract has changed


*January 12, 2021*

### Changed
- 'jet' theme instead of 'je'
- Updated config for latest `sass-loader`.
- Switches import in `common.scss` in line with fozzie v5-beta.
- Update axios version for security advisory

### Added
- Stylelint added to lint styling on build.


v1.0.0-beta.1
------------------------------
*September 3, 2020*

### Changed
- Rebasing `v0.3.0` changes into the beta branch.


v1.0.0-beta.0
------------------------------
*August 27, 2020*

### Changed
- Uses `JustEatBasis` font and new fozzie font size declarations.


v0.3.1
------------------------------
*September 8, 2020*

### Changed
- `eslint-config-fozzie` & `f-trak` peer dependencies use a range value.


v0.3.0
------------------------------
*August 28, 2020*

### Changed
- Removed component top margin. This should be set in the host app, if required
- Updated packages. Reduced bundle size


v0.2.0
------------------------------
*July 23, 2020*

### Changed
- Small update to colours from updating to `fozzie-colour-palette` in the mono-repo root.
- Vue CLI minor package updates.


v0.1.1
------------------------------
*May 12, 2020*

### Changed
- Updating `vue-test-utils` to v1 and `@vue/cli-plugin-unit-test` to v4.3.1.
- ESLint autofix turned off (so that tests don't pass due to `--fix` being applied, but then publish subsequently fails)

### Removed
- `testMatch` from jest config, as not needed.


v0.1.0
------------------------------
*March 27, 2020*

### Added
- Adds `f-user-message` vue component
