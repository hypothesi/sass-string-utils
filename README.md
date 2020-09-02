# SASS/SCSS String Utils

A small utility library for string manipulation functions in SASS/SCSS.

[Read the full function documentation.](https://hypothesi.github.io/sass-string-utils)

## Getting Started

```bash
npm install @hypothesi/sass-string-utils
```

Import string utils into your SCSS:

```scss
@use './node_modules/@hypothesi/sass-string-utils' as strUtils;

// Example usage
@debug strUtils.kebab-to-camel-case('background-color'); // Outputs backgroundColor
```
