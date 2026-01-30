# CHANGELOG

> Package changelog.

<section class="release" id="v0.3.0">

## 0.3.0 (2026-01-30)

<section class="features">

### Features

-   [`f0bc703`](https://github.com/stdlib-js/stdlib/commit/f0bc703d30986a4f1c75a97f7b8928dc8bfd0dc2) - add C implementation for `stats/base/dists/poisson/cdf`
-   [`2f3cca7`](https://github.com/stdlib-js/stdlib/commit/2f3cca7d06afd7bf32b641d9620886625ae97d53) - add C implementation for `stats/base/dists/poisson/mgf` [(#4626)](https://github.com/stdlib-js/stdlib/pull/4626)
-   [`c38ee71`](https://github.com/stdlib-js/stdlib/commit/c38ee71d49e745de331e6bce1a78493676f962b4) - add C implementation of `stats/base/dists/poisson/logpmf` [(#5194)](https://github.com/stdlib-js/stdlib/pull/5194)
-   [`cee6330`](https://github.com/stdlib-js/stdlib/commit/cee6330690f51588e8fc2796f1f928d33d14d9b9) - add C implementation for `stats/base/dists/poisson/skewness` [(#4023)](https://github.com/stdlib-js/stdlib/pull/4023)
-   [`36a00f3`](https://github.com/stdlib-js/stdlib/commit/36a00f394a0692b67b9556122978f26b8103452a) - add C implementation for `stats/base/dists/poisson/mode` [(#4019)](https://github.com/stdlib-js/stdlib/pull/4019)
-   [`e37cd0e`](https://github.com/stdlib-js/stdlib/commit/e37cd0eba13fa6acb6488f44b710502057d4cfc4) - add C implementation for `stats/base/dists/poisson/kurtosis` [(#4032)](https://github.com/stdlib-js/stdlib/pull/4032)
-   [`ad92859`](https://github.com/stdlib-js/stdlib/commit/ad92859bc6c33d55d94fdc7f8430f5d7a52afbab) - add C implementation for `stats/base/dists/poisson/median` [(#4018)](https://github.com/stdlib-js/stdlib/pull/4018)
-   [`84d202a`](https://github.com/stdlib-js/stdlib/commit/84d202aa314bdc0e2de1975f806cab8d6a2d3ffc) - add C implementation for  `stats/base/dists/poisson/stdev` [(#4030)](https://github.com/stdlib-js/stdlib/pull/4030)
-   [`3550fc4`](https://github.com/stdlib-js/stdlib/commit/3550fc4a653ce3d56e01a36752dd5e9f47db3586) - add C implementation for `@stdlib/stats-base/dists/poisson/mean` [(#3973)](https://github.com/stdlib-js/stdlib/pull/3973)
-   [`0e2d82a`](https://github.com/stdlib-js/stdlib/commit/0e2d82a0e55b279370365e56b765922321a69e05) - add C implementation for `stats/base/dists/poisson/variance` [(#3933)](https://github.com/stdlib-js/stdlib/pull/3933)

</section>

<!-- /.features -->

<section class="bug-fixes">

### Bug Fixes

-   [`be4189e`](https://github.com/stdlib-js/stdlib/commit/be4189e889c15276e3cba0f176bd0597fbdc299b) - remove unused includes
-   [`bdf9a93`](https://github.com/stdlib-js/stdlib/commit/bdf9a9377e6412ba4e2d24f7619d88e344d62b54) - add missing dep, update description, and revert test changes

</section>

<!-- /.bug-fixes -->

<section class="issues">

### Closed Issues

A total of 12 issues were closed in this release:

[#3787](https://github.com/stdlib-js/stdlib/issues/3787), [#3788](https://github.com/stdlib-js/stdlib/issues/3788), [#3789](https://github.com/stdlib-js/stdlib/issues/3789), [#3790](https://github.com/stdlib-js/stdlib/issues/3790), [#3791](https://github.com/stdlib-js/stdlib/issues/3791), [#3792](https://github.com/stdlib-js/stdlib/issues/3792), [#3795](https://github.com/stdlib-js/stdlib/issues/3795), [#3796](https://github.com/stdlib-js/stdlib/issues/3796), [#3797](https://github.com/stdlib-js/stdlib/issues/3797), [#4984](https://github.com/stdlib-js/stdlib/issues/4984), [#5126](https://github.com/stdlib-js/stdlib/issues/5126), [#6432](https://github.com/stdlib-js/stdlib/issues/6432)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`93fa3eb`](https://github.com/stdlib-js/stdlib/commit/93fa3eb4ae84a02ec231d778c6e543a83a86bc45) - **docs:** replace manual `for` loop in examples [(#9440)](https://github.com/stdlib-js/stdlib/pull/9440) _(by Harsh Yadav, Athan Reines)_
-   [`97218a1`](https://github.com/stdlib-js/stdlib/commit/97218a12e1d5ec1479a5b39ac4d32318c372e922) - **docs:** fix TSDoc example code return annotations _(by Philipp Burckhardt)_
-   [`e2efe32`](https://github.com/stdlib-js/stdlib/commit/e2efe32914d0d9dae5da34e6f7e7bf7655430710) - **chore:** rename exported variable in d.ts file to match name used in example code _(by Philipp Burckhardt)_
-   [`776887e`](https://github.com/stdlib-js/stdlib/commit/776887e9577ae2402fd69c97328cb864811bd120) - **docs:** update annotation values _(by Philipp Burckhardt)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`fc438e0`](https://github.com/stdlib-js/stdlib/commit/fc438e0edbad0689d6923d6f3edb959b96597662) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`11581aa`](https://github.com/stdlib-js/stdlib/commit/11581aaca8c3cb824cbb92c0c0f80e76890bdb20) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`07f7c05`](https://github.com/stdlib-js/stdlib/commit/07f7c0522c73e6ad9505e1d45035ae439344200d) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`9c21fd2`](https://github.com/stdlib-js/stdlib/commit/9c21fd20ef8b8a6a88abb96d80ea6d8e4c5434eb) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`a77644a`](https://github.com/stdlib-js/stdlib/commit/a77644ac6d491ff8693b0b02315b52a3d1659172) - **bench:** fix import path _(by Athan Reines)_
-   [`c19cc6b`](https://github.com/stdlib-js/stdlib/commit/c19cc6bfcccf04aede87a6cb69578117db09704b) - **chore:** clean-up _(by Athan Reines)_
-   [`f0bc703`](https://github.com/stdlib-js/stdlib/commit/f0bc703d30986a4f1c75a97f7b8928dc8bfd0dc2) - **feat:** add C implementation for `stats/base/dists/poisson/cdf` _(by Philipp Burckhardt)_
-   [`be4189e`](https://github.com/stdlib-js/stdlib/commit/be4189e889c15276e3cba0f176bd0597fbdc299b) - **fix:** remove unused includes _(by Philipp Burckhardt)_
-   [`07cc4a4`](https://github.com/stdlib-js/stdlib/commit/07cc4a4f1aeec8d7d197d47b8a0db66be06a44f9) - **test:** align test descriptions between main and native test files _(by Philipp Burckhardt)_
-   [`c499a2b`](https://github.com/stdlib-js/stdlib/commit/c499a2b50d272eb567a8b670d5a0558e163f83a1) - **test:** update variables and remove references to range _(by Philipp Burckhardt)_
-   [`4b136ff`](https://github.com/stdlib-js/stdlib/commit/4b136ff38994cd60151a6271312222c699e0d2f0) - **test:** update main MGF tests to match native ones and align tolerances _(by Philipp Burckhardt)_
-   [`2f3cca7`](https://github.com/stdlib-js/stdlib/commit/2f3cca7d06afd7bf32b641d9620886625ae97d53) - **feat:** add C implementation for `stats/base/dists/poisson/mgf` [(#4626)](https://github.com/stdlib-js/stdlib/pull/4626) _(by Aadish Jain, Philipp Burckhardt, stdlib-bot)_
-   [`c24ea87`](https://github.com/stdlib-js/stdlib/commit/c24ea877723f2ac751abb70e8d3f38362f846a43) - **test:** add missing skips for native add-on tests _(by Philipp Burckhardt)_
-   [`33ba5a0`](https://github.com/stdlib-js/stdlib/commit/33ba5a0d301d47b4d950ca6ed548dcc4a5bcc1a1) - **test:** add missing skips for native add-on tests _(by Philipp Burckhardt)_
-   [`bdf9a93`](https://github.com/stdlib-js/stdlib/commit/bdf9a9377e6412ba4e2d24f7619d88e344d62b54) - **fix:** add missing dep, update description, and revert test changes _(by Athan Reines)_
-   [`c38ee71`](https://github.com/stdlib-js/stdlib/commit/c38ee71d49e745de331e6bce1a78493676f962b4) - **feat:** add C implementation of `stats/base/dists/poisson/logpmf` [(#5194)](https://github.com/stdlib-js/stdlib/pull/5194) _(by Saurabh Singh, Philipp Burckhardt)_
-   [`cee6330`](https://github.com/stdlib-js/stdlib/commit/cee6330690f51588e8fc2796f1f928d33d14d9b9) - **feat:** add C implementation for `stats/base/dists/poisson/skewness` [(#4023)](https://github.com/stdlib-js/stdlib/pull/4023) _(by Manvith M, Philipp Burckhardt, stdlib-bot)_
-   [`36a00f3`](https://github.com/stdlib-js/stdlib/commit/36a00f394a0692b67b9556122978f26b8103452a) - **feat:** add C implementation for `stats/base/dists/poisson/mode` [(#4019)](https://github.com/stdlib-js/stdlib/pull/4019) _(by Manvith M, Philipp Burckhardt, stdlib-bot)_
-   [`e37cd0e`](https://github.com/stdlib-js/stdlib/commit/e37cd0eba13fa6acb6488f44b710502057d4cfc4) - **feat:** add C implementation for `stats/base/dists/poisson/kurtosis` [(#4032)](https://github.com/stdlib-js/stdlib/pull/4032) _(by Manvith M, Philipp Burckhardt, stdlib-bot)_
-   [`ad92859`](https://github.com/stdlib-js/stdlib/commit/ad92859bc6c33d55d94fdc7f8430f5d7a52afbab) - **feat:** add C implementation for `stats/base/dists/poisson/median` [(#4018)](https://github.com/stdlib-js/stdlib/pull/4018) _(by Manvith M, Philipp Burckhardt, stdlib-bot)_
-   [`84d202a`](https://github.com/stdlib-js/stdlib/commit/84d202aa314bdc0e2de1975f806cab8d6a2d3ffc) - **feat:** add C implementation for  `stats/base/dists/poisson/stdev` [(#4030)](https://github.com/stdlib-js/stdlib/pull/4030) _(by Manvith M, Philipp Burckhardt, stdlib-bot)_
-   [`b0c4a5a`](https://github.com/stdlib-js/stdlib/commit/b0c4a5aa2bfd9f4a1660b202ed8eb30759bcf1e7) - **chore:** fix EditorConfig lint errors [(#6931)](https://github.com/stdlib-js/stdlib/pull/6931) _(by Lalit Narayan Yadav)_
-   [`5f73301`](https://github.com/stdlib-js/stdlib/commit/5f73301a8509cc423a06b02140c4e316fd02ff49) - **docs:** minor clean-up _(by Philipp Burckhardt)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`f7988d3`](https://github.com/stdlib-js/stdlib/commit/f7988d3c02e0eff3bd9bd7523b5dc975bb98dc0e) - **bench:** fix `isnan` checks in `stats/base/dists` [(#5296)](https://github.com/stdlib-js/stdlib/pull/5296) _(by Karan Anand)_
-   [`e61b1de`](https://github.com/stdlib-js/stdlib/commit/e61b1dee3334bacf30d213de5b5f1c7868c0753b) - **docs:** clean-up of C docstrings _(by Philipp Burckhardt)_
-   [`bd61ef0`](https://github.com/stdlib-js/stdlib/commit/bd61ef01645b4128484f9a87532724fdba990c03) - **bench:** address commit comments [(#5137)](https://github.com/stdlib-js/stdlib/pull/5137) _(by pranav-1720)_
-   [`ba0c854`](https://github.com/stdlib-js/stdlib/commit/ba0c854e87d0e86d0f7739e26095ec0a0f40c36f) - **docs:** fix function names in C example code _(by Philipp Burckhardt)_
-   [`28b78a0`](https://github.com/stdlib-js/stdlib/commit/28b78a0590907a6757bc6fd4c9e88d9109280950) - **bench:** refactor random number generation in `stats/base/dists/poisson` [(#5106)](https://github.com/stdlib-js/stdlib/pull/5106) _(by pranav-1720)_
-   [`b7867cb`](https://github.com/stdlib-js/stdlib/commit/b7867cbb3a4fc453e19203794402c36f19b264fd) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`8bf8285`](https://github.com/stdlib-js/stdlib/commit/8bf8285aba0ecbd00ae145c4c5c098cd28135814) - **chore:** minor clean-up _(by Philipp Burckhardt)_
-   [`3550fc4`](https://github.com/stdlib-js/stdlib/commit/3550fc4a653ce3d56e01a36752dd5e9f47db3586) - **feat:** add C implementation for `@stdlib/stats-base/dists/poisson/mean` [(#3973)](https://github.com/stdlib-js/stdlib/pull/3973) _(by Divyansh Seth, Philipp Burckhardt)_
-   [`0e2d82a`](https://github.com/stdlib-js/stdlib/commit/0e2d82a0e55b279370365e56b765922321a69e05) - **feat:** add C implementation for `stats/base/dists/poisson/variance` [(#3933)](https://github.com/stdlib-js/stdlib/pull/3933) _(by Aayush Khanna, Philipp Burckhardt, stdlib-bot)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 11 people contributed to this release. Thank you to the following contributors:

-   Aadish Jain
-   Aayush Khanna
-   Athan Reines
-   Divyansh Seth
-   Harsh Yadav
-   Karan Anand
-   Lalit Narayan Yadav
-   Manvith M
-   Philipp Burckhardt
-   Saurabh Singh
-   pranav-1720

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-28)

<section class="commits">

### Commits

<details>

-   [`c3ebfa8`](https://github.com/stdlib-js/stdlib/commit/c3ebfa80e311db338b171ebf8eb5f46bc66e9bf6) - **docs:** update namespace table of contents and address spelling errors _(by Philipp Burckhardt)_
-   [`41d41e9`](https://github.com/stdlib-js/stdlib/commit/41d41e959b4eaad3c631e6898e3144a4015a5458) - **test:** include trailing newlines in Julia-generated JSON fixtures _(by Philipp Burckhardt)_
-   [`9ed7d0e`](https://github.com/stdlib-js/stdlib/commit/9ed7d0e7d57edb5ad0dfb65c944bed87d475cbf3) - **chore:** add missing trailing newlines _(by Philipp Burckhardt)_
-   [`d66f5d6`](https://github.com/stdlib-js/stdlib/commit/d66f5d6f7a564b08f57fa210c63a311e5f76df10) - **docs:** improve README examples of `stats/base/dists/poisson` namespace _(by Nishant Shinde, Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Nishant Shinde
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="commits">

### Commits

<details>

-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="features">

### Features

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`d5fa8e8`](https://github.com/stdlib-js/stdlib/commit/d5fa8e8a6267a837a25a7027e9fe3e847bc2d1c5) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`ce7e336`](https://github.com/stdlib-js/stdlib/commit/ce7e3367c0f9477773fe76dd0eca64dc6ad33c02) - **docs:** update equations _(by Philipp Burckhardt)_
-   [`37f032d`](https://github.com/stdlib-js/stdlib/commit/37f032d4a571f667ea99f6f52f60b5d736c627f3) - **docs:** render equations via math code blocks _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-07-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

