RTL-Sass
========

v0.0.7

## What is it?

RTL-Sass provides mixins and functions to automatically flip your CSS styles for RTL (right-to-left) pages.

Supports flipping the following properties:

- background
- background-position
- border
- border-radius
- clear
- cursor
- direction
- float
- left/right
- margin
- padding
- text-align
- text-indent

These mixins are for use with Sass (http://sass-lang.com/).

## Usage

Coming soon...

## Change log

### 0.0.7

- Add support for backgrounds which have horizontal positioning set in percent (%)
- Add support for background shorthands with 6 values
- Add support for `cursor`: `ne-resize`, `e-resize`, `se-resize`, `sw-resize`, `w-resize`, `nw-resize`

### 0.0.6

- Add support for backgrounds which are centred using `50%` instead of `center`

### 0.0.5

- indent properties and align values
- add mixins `margin()`, `padding()` and `border-width()`
- remove `lrswap2()`: no critical use case and confusing
- `$rtl` has a default value
- prefer `$value` and `$values` instead of `$val`, more explicit
- tests are in a separate file

### 0.0.4

- Added support for `direction`
- Reorder mixins alphabetically
- Added demo page

### 0.0.3

- Sample css files
- Added support for `background`, `background-position`, `clear` and `text-align`

### 0.0.2

- Refining mixins to look more like normal CSS
- Added support for `border-radius` and `text-indent`
- Added a universal swap mixin that can take any property that has 4 values

### 0.0.1

- Initial release
- Support for `float`, `padding`, `margin`, `border` and `position`
