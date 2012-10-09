RTL-Sass
========

v0.0.5

http://jalproductions.co.uk/

## What is it?

RTL-Sass provides mixins and functions to automatically flip your CSS styles for RTL (right-to-left) documents.

Supports flipping the following properties:

- background
- background-position
- border
- border-radius
- clear
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

### 0.0.5

- indent properties and align values
- add mixing `margin()`, `padding()` and `border-width()`
- remove `lrswap2()`: no really critical use case & confusing
- `$rtl` has a default value
- prefer `$val` to `$value` and `$values`, more explicit
- tests are in a separate file

### 0.0.4

- Added support for direction
- Reorder mixins alphabetically
- Added demo page

### 0.0.3

- Sample css files
- Added support for background, background-position, clear and text-align

### 0.0.2

- Refining mixins to look more like normal CSS
- Added support for border-radius and text indent
- Added a universal swap mixin that can take any property that has 4 values

### 0.0.1

- Initial release
- Support for float, padding, margin, border and position
