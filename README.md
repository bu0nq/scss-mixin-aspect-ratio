# SCSS Mixin Aspect Ratio

A package for integrating a mixin to create proportional blocks.

![npm](https://img.shields.io/npm/v/@bu0nq/scss-mixin-aspect-ratio?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@bu0nq/scss-mixin-aspect-ratio?style=for-the-badge)

Documentation: [EN](README.md) | [RU](README.RU.md)

___

## Installation

You can install the package automatically using NPM:

```
npm i @bu0nq/scss-mixin-aspect-ratio
```

## Usage

To use the package, import it into your project:

```scss
@use "@bu0nq/scss-mixin-aspect-ratio" as *;

.demo {
    @include aspect-ratio(1, 1) {
        // Styles
    };
}
```

## Changing the namespace

You can change the namespace during mixin import and use the mixin with a different namespace:

```scss
@use "@bu0nq/scss-mixin-aspect-ratio" as mixin;

.demo {
    @include mixin.aspect-ratio(1, 1) {
        // Styles
    };
}
```
