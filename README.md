[![npm](https://img.shields.io/npm/v/@mediamonks/scss-utils.svg?maxAge=2592000)](https://www.npmjs.com/package/@mediamonks/scss-utils)
[![npm](https://img.shields.io/npm/dm/@mediamonks/scss-utils.svg?maxAge=2592000)](https://www.npmjs.com/package/@mediamonks/scss-utils)

# @mediamonks/scss-utils

A SCSS library of mixins and functions that are used within projects.

## Installation

### yarn

```shell
$ yarn add -D @mediamonks/scss-utils
```
### npm

```sh
npm i -S @mediamonks/scss-utils
```

## Included functionalities

### Mixins

-   [aspect-ratio](./utils/mixin/_aspect-ratio.scss)
-   [font-face](./utils/mixin/_font-face.scss)
-   [hover](./utils/mixin/_hover.scss)
-   [ir](./utils/mixin/_image-replacement.scss)
-   [placeholder](./utils/mixin/_placeholder.scss)
-   [position](./utils/mixin/_position.scss)
-   [offset](./utils/mixin/_offset.scss)
-   [pseudo](./utils/mixin/_pseudo.scss)
-   [respond-to](./utils/mixin/_respond-to.scss)
-   [size](./utils/mixin/_size.scss)
-   [screen-reader-only](./utils/mixin/_screen-reader-only.scss)
-   [text-ellipsis](./utils/mixin/_text-ellipsis.scss)
-   [arrow](./utils/mixin/shape/_arrow.scss)

### Functions

-   [asset / image / font](./utils/function/_asset.scss)
-   [index](./utils/function/_zindex.scss)
-   [em-size](./utils/function/_em-size.scss)
-   [font-weight](./utils/function/_font-weight.scss)
-   [strip-unit](./utils/function/_strip-unit.scss)
-   [remify](./utils/function/_remify.scss)
-   [fluid-size](./utils/function/_fluid-size.scss)

### Variables

-   [variables](./utils/_variables.scss)
    -   **$pathAsset**: default project asset path (..)
    -   **$pathFont**: default project font path (font, prefixed with $pathAsset)
    -   **$pathImage**: default project image path (image, prefixed with $pathAsset)
    -   **$zLayout**: default list of zIndex names (default)
    -   **$mediaQueries**: default list of mediaQueries (empty list)
    -   **$minimumFluidSizeViewportWidth**: default value for minumum viewport width used in fluid size (480px)
    -   **$maximumFluidSizeViewportWidth**: default value for maximum viewport width used in fluid size (1440px)
    -   **$useRem**: default value for using/converting pixels into REM units in fluid size (true)
    -   **$useClamp**: default value for using `clamp` (otherwise `max`) in fluid size (true)
    -   **$ease{name}**: List of easing bezier curves
        -   **$easeLinear**
            -   **$ease**
            -   **$easeIn**
            -   **$easeOut**
            -   **$easeInOut**
            -   **$easeInQuad**
            -   **$easeOutQuad**
            -   **$easeInCubic**
            -   **$easeOutCubic**
            -   **$easeInQuart**
            -   **$easeOutQuart**
            -   **$easeInQuint**
            -   **$easeOutQuint**
            -   **$easeInSine**
            -   **$easeOutSine**
            -   **$easeInExpo**
            -   **$easeOutExpo**
            -   **$easeInCirc**
            -   **$easeOutCirc**
            -   **$easeInBack**
            -   **$easeOutBack**
            -   **$easeInOutQuad**
            -   **$easeInOutCubic**
            -   **$easeInOutQuart**
            -   **$easeInOutQuint**
            -   **$easeInOutSine**
            -   **$easeInOutExpo**
            -   **$easeInOutCirc**
            -   **$easeInOutBack**

## Contribute

View [CONTRIBUTING.md](./CONTRIBUTING.md)

## Changelog

View [CHANGELOG.md](./CHANGELOG.md)

## Authors

View [AUTHORS.md](./AUTHORS.md)

## LICENSE

[MIT](./LICENSE) © MediaMonks
