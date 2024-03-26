# Changelog

## [3.8.0](https://github.com/kirademiurge/reatom/compare/effects-v3.7.2...effects-v3.8.0) (2024-03-26)


### Features

* **effects:** add abortCauseContext ([af28718](https://github.com/kirademiurge/reatom/commit/af28718598a852ba7926e54cd5f1b6a508441951))
* **effects:** add CauseContext ([65baab5](https://github.com/kirademiurge/reatom/commit/65baab5cdc1256619b1fa779376f3e7508fc0c8d))
* **effects:** add concurrent ([21b824b](https://github.com/kirademiurge/reatom/commit/21b824b939bd6bd57b3d33d8eaa91ea67d784c41))
* **effects:** add isCausedBy ([02a6406](https://github.com/kirademiurge/reatom/commit/02a64069e272387cb64b1573a765a3d70abac825))
* **effects:** add isInit method ([4a8aeb1](https://github.com/kirademiurge/reatom/commit/4a8aeb14d0cdf54a545dda498c026e8f9b7c29d2))
* **effects:** add spawn ([2eab5cb](https://github.com/kirademiurge/reatom/commit/2eab5cbc6b26450b09ed43ad9cb815a997950c1d))
* **effects:** add withAbortableSchedule ([9e219a7](https://github.com/kirademiurge/reatom/commit/9e219a7d61c18cc15bcff28f310938166d10de2c))
* **effects:** change the behavior of __thenReatomed ([6a7ccba](https://github.com/kirademiurge/reatom/commit/6a7ccba6a46521807d5d1e5eef3c3ad219454779))
* **effects:** skip mark for take filter ([c136bd8](https://github.com/kirademiurge/reatom/commit/c136bd884df59715ea8a4028e29eaa3e1dc6b076))


### Bug Fixes

* **effects:** __thenReatomed error propagation ([6a7536f](https://github.com/kirademiurge/reatom/commit/6a7536f7b5afcad22fc90fc0afbfc7b71bfd71ec))
* **effects:** add has method to CauseContext ([0b442c1](https://github.com/kirademiurge/reatom/commit/0b442c1fdbb119c2828951aff0b97d490efdb397))
* **effects:** concurrent nested aborts ([6cc5dc4](https://github.com/kirademiurge/reatom/commit/6cc5dc45c8f6bb9e51c2fd76c7b6dda7352ce4c2))
* **effects:** concurrent.abortControllerAtom name ([25bdc47](https://github.com/kirademiurge/reatom/commit/25bdc479e62045f946aeee6b9e001a8cb3450a07))
* **effects:** improve onCtxAbort ([16ee497](https://github.com/kirademiurge/reatom/commit/16ee497b08810aef908bcd7b2b2e7151d5f4ff12))
* **effects:** more friendly typings for isCausedBy ([5d60c1d](https://github.com/kirademiurge/reatom/commit/5d60c1da8710c90df60b24e5d013e829455260d0))
* **effects:** onCtxAbort for sync and async usage ([bc52760](https://github.com/kirademiurge/reatom/commit/bc52760aa54d767744ba07ce17124d1f48f0a4ee))
* **effects:** prevent Uncaught DOMException for aborts ([79f719b](https://github.com/kirademiurge/reatom/commit/79f719bbdd6e97cb56c3399a841c33764822d598))
* **effects:** prevent uncaught rejection for the abort of the concurrent API ([028bf10](https://github.com/kirademiurge/reatom/commit/028bf10baa38bcd85d6ae7445c8294160b50ca07))
* **effects:** prevent unhandled error for abort ([fe884e2](https://github.com/kirademiurge/reatom/commit/fe884e24ac574fc50c7ce4e825459d7059136b73))
* **effects:** withAbortableSchedule ([399d36f](https://github.com/kirademiurge/reatom/commit/399d36ffb00d3597fa9c234358b8c50a6aeb8a7a))
* **effects:** withAbortableSchedule sync abort ([ebede8d](https://github.com/kirademiurge/reatom/commit/ebede8d8f652da58bf2e29d6b5ec58966199059b))

## [3.7.2](https://github.com/artalar/reatom/compare/effects-v3.7.1...effects-v3.7.2) (2023-11-25)


### Bug Fixes

* **effects:** more friendly typings for isCausedBy ([5d60c1d](https://github.com/artalar/reatom/commit/5d60c1da8710c90df60b24e5d013e829455260d0))
* **effects:** prevent unhandled error for abort ([fe884e2](https://github.com/artalar/reatom/commit/fe884e24ac574fc50c7ce4e825459d7059136b73))

## [3.7.1](https://github.com/artalar/reatom/compare/effects-v3.7.0...effects-v3.7.1) (2023-11-23)


### Bug Fixes

* **effects:** concurrent.abortControllerAtom name ([25bdc47](https://github.com/artalar/reatom/commit/25bdc479e62045f946aeee6b9e001a8cb3450a07))
* **effects:** prevent uncaught rejection for the abort of the concurrent API ([028bf10](https://github.com/artalar/reatom/commit/028bf10baa38bcd85d6ae7445c8294160b50ca07))

## [3.7.0](https://github.com/artalar/reatom/compare/effects-v3.6.0...effects-v3.7.0) (2023-11-20)


### Features

* **effects:** add abortCauseContext ([af28718](https://github.com/artalar/reatom/commit/af28718598a852ba7926e54cd5f1b6a508441951))
* **effects:** add concurrent ([21b824b](https://github.com/artalar/reatom/commit/21b824b939bd6bd57b3d33d8eaa91ea67d784c41))
* **effects:** add spawn ([2eab5cb](https://github.com/artalar/reatom/commit/2eab5cbc6b26450b09ed43ad9cb815a997950c1d))


### Bug Fixes

* **effects:** concurrent nested aborts ([6cc5dc4](https://github.com/artalar/reatom/commit/6cc5dc45c8f6bb9e51c2fd76c7b6dda7352ce4c2))

## [3.6.0](https://github.com/artalar/reatom/compare/effects-v3.5.1...effects-v3.6.0) (2023-10-20)


### Features

* **effects:** add isInit method ([4a8aeb1](https://github.com/artalar/reatom/commit/4a8aeb14d0cdf54a545dda498c026e8f9b7c29d2))
* **effects:** skip mark for take filter ([c136bd8](https://github.com/artalar/reatom/commit/c136bd884df59715ea8a4028e29eaa3e1dc6b076))


### Bug Fixes

* **effects:** withAbortableSchedule ([399d36f](https://github.com/artalar/reatom/commit/399d36ffb00d3597fa9c234358b8c50a6aeb8a7a))

## [3.5.1](https://github.com/artalar/reatom/compare/effects-v3.5.0...effects-v3.5.1) (2023-09-14)


### Bug Fixes

* **effects:** withAbortableSchedule sync abort ([ebede8d](https://github.com/artalar/reatom/commit/ebede8d8f652da58bf2e29d6b5ec58966199059b))

## [3.5.0](https://github.com/artalar/reatom/compare/effects-v3.4.0...effects-v3.5.0) (2023-09-13)


### Features

* **effects:** add withAbortableSchedule ([9e219a7](https://github.com/artalar/reatom/commit/9e219a7d61c18cc15bcff28f310938166d10de2c))


### Bug Fixes

* **effects:** prevent Uncaught DOMException for aborts ([79f719b](https://github.com/artalar/reatom/commit/79f719bbdd6e97cb56c3399a841c33764822d598))

## [3.4.0](https://github.com/artalar/reatom/compare/effects-v3.3.1...effects-v3.4.0) (2023-08-05)


### Features

* **effects:** add CauseContext ([65baab5](https://github.com/artalar/reatom/commit/65baab5cdc1256619b1fa779376f3e7508fc0c8d))
* **effects:** add isCausedBy ([02a6406](https://github.com/artalar/reatom/commit/02a64069e272387cb64b1573a765a3d70abac825))


### Bug Fixes

* **effects:** add has method to CauseContext ([0b442c1](https://github.com/artalar/reatom/commit/0b442c1fdbb119c2828951aff0b97d490efdb397))

## [3.3.1](https://github.com/artalar/reatom/compare/effects-v3.3.0...effects-v3.3.1) (2023-07-07)


### Bug Fixes

* **effects:** __thenReatomed error propagation ([6a7536f](https://github.com/artalar/reatom/commit/6a7536f7b5afcad22fc90fc0afbfc7b71bfd71ec))
* **effects:** improve onCtxAbort ([16ee497](https://github.com/artalar/reatom/commit/16ee497b08810aef908bcd7b2b2e7151d5f4ff12))

## [3.3.0](https://github.com/artalar/reatom/compare/effects-v3.2.1...effects-v3.3.0) (2023-06-12)


### Features

* **effects:** change the behavior of __thenReatomed ([6a7ccba](https://github.com/artalar/reatom/commit/6a7ccba6a46521807d5d1e5eef3c3ad219454779))


### Bug Fixes

* **effects:** onCtxAbort for sync and async usage ([bc52760](https://github.com/artalar/reatom/commit/bc52760aa54d767744ba07ce17124d1f48f0a4ee))

## [3.2.1](https://github.com/artalar/reatom/compare/effects-v3.2.0...effects-v3.2.1) (2023-05-21)


### Bug Fixes

* **all-settled:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **async:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **core-v1:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **core-v2:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **core:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **effects:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **eslint-plugin:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **form-web:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **form:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **framework:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **hooks:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **lens:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **logger:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **navigation:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* new way of hooking up typings [#560](https://github.com/artalar/reatom/issues/560) ([#568](https://github.com/artalar/reatom/issues/568)) ([99550e9](https://github.com/artalar/reatom/commit/99550e98c34df7efd8431282a868a0483bed5dc8))
* **npm-cookie-baker:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **npm-history:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **npm-lit:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **npm-react:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **npm-svelte:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **persist-web-storage:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **persist:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **primitives:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **react-v1:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **react-v2:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **testing:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **timer:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **undo:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
* **utils:** change build output ([5bedebd](https://github.com/artalar/reatom/commit/5bedebda3a1ee92850d10f767686303b8ec2ba0e))
