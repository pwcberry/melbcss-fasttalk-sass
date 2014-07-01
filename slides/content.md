# SCSS: Overview

## What is it?

* Pre-processor
* Enhances CSS with programming idioms
* Runs on Ruby

# Show us some code

## Variables

## Operators

* string concatenator

## Directives

* `@if \ @else`
* `@for`
* `@each`
* `@while`
* `@extend`

## Mixins

    @mixin large-text {
      font: {
        family: Arial;
        size: 20px;
        weight: bold;
      }
      color: #ff0000;
    }
    
To use a mixin:

    h1 {
        @include large-text;
    }
    
* variable arguments
* a map can be passed as the argument to a mixin, and the key / values will be matched to the defined parameters

* content blocks for a mixin

## Built-in Functions

* `opacify`
* `transparentize`
* `hsl`
* `mix`
* `saturate`
* `desaturate`
* `grayscale`
* `lighten`
* `darken`

### Function directives

# Bundled with

* Ruby on Rails
* Jekyll

# Compared to LESS

Less doesn't have:

* `@include`
* `$map (key1: value1, key2: value2)`

# Frameworks

* Compass (demo & code sample)
* Bourbon (demo & code sample)


# Resources

* [sass-lang.com](http://sass-lang.com)
* [Sass documentation](http://sass-lang.com/documentation/file.SASS_REFERENCE.html)
* [Sass functions](http://sass-lang.com/documentation/Sass/Script/Functions.html)
* [Compass](http://compass-style.org/)
* [Bourbon](http://bourbon.io/)
* [Ruby installer for Windows](http://rubyinstaller.org/)
