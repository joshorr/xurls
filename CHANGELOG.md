# Changelog

## [1.4.0](https://github.com/joshorr/xurls/compare/v1.3.0...v1.4.0) (2025-09-30)


### Features

* add metadata option to Url. ([cd3f330](https://github.com/joshorr/xurls/commit/cd3f3301a2b09399cc6d5151d36d425c675dd9af))

## [1.3.0](https://github.com/joshorr/xurls/compare/v1.2.1...v1.3.0) (2025-08-08)


### Features

* add make suffix  '__in!' work ([0297cfd](https://github.com/joshorr/xurls/commit/0297cfd1d9fedc8f3b546ffaf6e10ec2949b7001))


### Bug Fixes

* add '__in!' as suffix to keep in url query strings ([ade4009](https://github.com/joshorr/xurls/commit/ade4009a93bd7facbeeceb59a04715a144c205bc))
* add '__in!' as suffix to keep in url query strings ([23996a7](https://github.com/joshorr/xurls/commit/23996a7c815d5c0a517b664bb78292fc35d5ff65))

## [1.2.1](https://github.com/joshorr/xurls/compare/v1.2.0...v1.2.1) (2024-09-04)


### Bug Fixes

* implementing `__len__` made the bool-value not what one would expect. ([08864d9](https://github.com/joshorr/xurls/commit/08864d9fa7d724f67c9200dc6e863e1b2eb4f320))

## [1.2.0](https://github.com/joshorr/xurls/compare/v1.1.0...v1.2.0) (2024-09-04)


### Features

* use url like a dict to get/set/delete query values. ([f47c00d](https://github.com/joshorr/xurls/commit/f47c00dc55f39feefe07c3275b88f6e7b372a200))


### Documentation

* added example to readme. ([40cedb0](https://github.com/joshorr/xurls/commit/40cedb0df36092ddf63854bbc25e09f4b3b98b10))

## [1.1.0](https://github.com/joshorr/xurls/compare/v1.0.0...v1.1.0) (2024-03-21)


### Features

* UUID already work as QueryValue; now formally declaring they work. ([d4ddfce](https://github.com/joshorr/xurls/commit/d4ddfce8d885081a4515e392f024490d5ea63b74))


### Bug Fixes

* update deps/lock-file. ([0d5655c](https://github.com/joshorr/xurls/commit/0d5655c10dcfd36abe6e398cb3ec393acd04384b))

## [1.0.0](https://github.com/joshorr/xurls/compare/v0.2.1...v1.0.0) (2023-12-19)


### Features

* add deprecation warnings + code formatting fixes. ([8f3e5d9](https://github.com/joshorr/xurls/commit/8f3e5d93a1dfb1144858ef56a438c77f266125fd))
* adjust tests to accommodate new Url class name. ([18bdd92](https://github.com/joshorr/xurls/commit/18bdd926fc28f60a842db4eaffb86cbd51678dca))
* deprecate the `Url.url` method, added `Url.format` as a replacement. ([9097016](https://github.com/joshorr/xurls/commit/90970168df672d6daafdd4fd23af4a4440f0ae25))
* Release version 1.0 ([1f8f596](https://github.com/joshorr/xurls/commit/1f8f596ca840eb71deb57602e4e4df0ba411ca97))
* remove frozen_url, may add back in someday but for now keep things simple and only have a single url class. ([1058df1](https://github.com/joshorr/xurls/commit/1058df154acf5bef0d7dc82c3c524e721bf44783))
* renamed URLMutable class to `Url`; removed `URL`; may make a FrozenUrl someday, but for now keeping it simple. ([6445bd8](https://github.com/joshorr/xurls/commit/6445bd8d668919ad0d572544df9f0af9a236fc24))
* update README with newer class names with slightly better examples. ([4f9993f](https://github.com/joshorr/xurls/commit/4f9993f752baef942eb5b3f9b008d116ae1feadb))

## [0.2.1](https://github.com/joshorr/xurls/compare/v0.2.0...v0.2.1) (2023-04-15)


### Bug Fixes

* license ([9986365](https://github.com/joshorr/xurls/commit/998636537d50f474946a95ff8d035ae61df58144))


### Documentation

* add doc links. ([39aa99e](https://github.com/joshorr/xurls/commit/39aa99eb1671356ca75ac1ae39be8f656e6b2967))

## [0.2.0](https://github.com/joshorr/xurls/compare/v0.1.1...v0.2.0) (2023-04-06)


### Features

* add docs ([18595a4](https://github.com/joshorr/xurls/commit/18595a4d9985265c716fc840377027b8003576e2))

## [0.1.1](https://github.com/joshorr/xurls/compare/v0.1.0...v0.1.1) (2023-04-05)


### Bug Fixes

* fix docs, so workflows work. ([f678315](https://github.com/joshorr/xurls/commit/f678315953957e4c6ee63e95f2171702edeba2d8))

## 0.1.0 (2023-04-05)


### Features

* initial starting code ([a3012c6](https://github.com/joshorr/xurls/commit/a3012c6ffb8f935301cce01f754112fa6ff60d10))
* publish for real. ([73d94f3](https://github.com/joshorr/xurls/commit/73d94f35a470191db4e16b003b660a71fd167543))
* remove unneeded refs, use xloop. ([ee74341](https://github.com/joshorr/xurls/commit/ee74341cdb0ddfcf65f3acccba0f6a6da633ea63))


### Bug Fixes

* project deps + toml file config. ([40ad409](https://github.com/joshorr/xurls/commit/40ad409c10a091f812a26d172b23c482cf4c223d))
