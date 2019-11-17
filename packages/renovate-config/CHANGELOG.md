# [@bigpopakap/renovate-config-v2.0.0](https://github.com/bigpopakap/shared-node-tools/compare/v1.0.0-@bigpopakap/renovate-config...v2.0.0-@bigpopakap/renovate-config) (2019-11-15)


### Features

* enable eslint-plugin-eslint-comments rules ([953a1b8](https://github.com/bigpopakap/shared-node-tools/commit/953a1b8d5a280b4979a248abf62528f50f579fcb)), closes [#92](https://github.com/bigpopakap/shared-node-tools/issues/92)
* enable eslint-plugin-node ([526b27d](https://github.com/bigpopakap/shared-node-tools/commit/526b27d92176414a9024b2d715b75c108f1b366f)), closes [#92](https://github.com/bigpopakap/shared-node-tools/issues/92)


### BREAKING CHANGES

* There are many rules enabled from here, which you may need to fix:
https://www.npmjs.com/package/eslint-plugin-node
* You may have to fix some of the rules related to improper use of eslint-disable
comments, described here: https://mysticatea.github.io/eslint-plugin-eslint-comments/rules/

# @bigpopakap/renovate-config-v1.0.0 (2019-11-15)


### Features

* publish to Github Packages ([1721d84](https://github.com/bigpopakap/shared-node-tools/commit/1721d84d0311daf02f8a1ccb508777e257a166ac)), closes [#86](https://github.com/bigpopakap/shared-node-tools/issues/86)


### BREAKING CHANGES

* This package is now being published to Github Packages. You should update your
.eslintrc file with the updated name of the package to extend from (described int he updated README)

# [renovate-config-bigpopakap-v1.1.2](https://github.com/bigpopakap/shared-node-tools/compare/v1.1.1-renovate-config-bigpopakap...v1.1.2-renovate-config-bigpopakap) (2019-11-14)


### Bug Fixes

* rename repo references ([3b5167b](https://github.com/bigpopakap/shared-node-tools/commit/3b5167be93b0908387009e3423191267d95c6860)), closes [#59](https://github.com/bigpopakap/shared-node-tools/issues/59)

# [renovate-config-bigpopakap-v1.1.1](https://github.com/bigpopakap/shared-node-tools/compare/v1.1.0-renovate-config-bigpopakap...v1.1.1-renovate-config-bigpopakap) (2019-11-04)


### Bug Fixes

* **ci:** fix autopublishing ([25b5002](https://github.com/bigpopakap/shared-node-tools/commit/25b50021f284aaae64579632a02fe26815d6b49a)), closes [#56](https://github.com/bigpopakap/shared-node-tools/issues/56)
* **package.json:** update repo link to point to subdirectories ([5ee5a6a](https://github.com/bigpopakap/shared-node-tools/commit/5ee5a6acad3345ab6d3f108a45e3f3ba2d844f49))

# [renovate-config-bigpopakap-v1.1.0](https://github.com/bigpopakap/shared-node-tools/compare/v1.0.0-renovate-config-bigpopakap...v1.1.0-renovate-config-bigpopakap) (2019-10-28)


### Features

* truncate commit message ([925b5bf](https://github.com/bigpopakap/shared-node-tools/commit/925b5bf5026f6bda4bb7a936fd6468cdc7f825bf)), closes [#39](https://github.com/bigpopakap/shared-node-tools/issues/39)

# renovate-config-bigpopakap-v1.0.0 (2019-10-16)


### Bug Fixes

* set initial version to 0.0.1 ([581afed](https://github.com/bigpopakap/shared-node-tools/commit/581afed0171d5ac52c15f5b4439eebd5d9afea99))


### Features

* configure package groups ([6fea7f1](https://github.com/bigpopakap/shared-node-tools/commit/6fea7f17d74217dc7f104ab3d71973e1ccf00ac0))
* enable renovate for peerDependencies ([f6208e0](https://github.com/bigpopakap/shared-node-tools/commit/f6208e0d03e691154e7d5c11c9903dd829777c4a)), closes [#12](https://github.com/bigpopakap/shared-node-tools/issues/12)
* **renovate-config-bipgopakap:** create new shareable renovate config ([401c97a](https://github.com/bigpopakap/shared-node-tools/commit/401c97aabaf4062df83663eb071fef5e4b043b53))