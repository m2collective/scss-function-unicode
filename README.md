# SCSS Function Unicode

A package for integrating functions that enable the creation of Unicode elements.

![npm](https://img.shields.io/npm/v/@m2collective/scss-function-unicode?style=for-the-badge)

___

## Installation

You can install the package automatically using NPM:

```
npm i @m2collective/scss-function-unicode
```

## Usage

To use the package, import it into your project:

```scss
@use "@m2collective/scss-function-unicode" as *;

.demo {
    &:before {
        content: unicode(\0041);
    }
}

// Return

.demo::before {
    content: '\0041';
}
```

## Changing the namespace

You can change the namespace during function import and use the function with a different namespace:

```scss
@use "@m2collective/scss-function-unicode" as function;
```

## License

The MIT License (MIT). Please see the [License file](LICENSE.txt) for more information.
