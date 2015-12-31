# stylep-bar
<img src=https://avatars1.githubusercontent.com/u/16121328?v=3&s=200 title=stylep-bar align=right height=95>

A basic element for making horizontal navigation bars. You can setup a bar with one or more `nav` sections.

## Install
You can install using the [spm](https://github.com/stylep/stylep) command or install using npm and the project name.

``` shell
spm install bar
```

## Usage
``` css
/* bar.css */

@import “stylep-bar”;

.bar-nav {

  /* Bar Design Pattern */
  @mixin bar-block;

  /* Customize your bar */
  @mixin bar-solid #333, #fff, 0 1px 5px rgba(0, 0, 0, .5);

  /* or roll your own */

  /* add something custom here */

	& nav > ul > li { }
}
```

## Patterns
Placeholder selectors that contain common styles for structure and basic behavior.

#### `bar-block`
Renders a div with a fixed size, gutter and padding.

##### Options

* `$bar-size: 58px`
* `$bar-gutter: 16px`
* `$bar-padding: .5em`
* `$bar-z-index: 100`

## Styles
Customizable presets that give your pattern a specific style-set.

#### `bar-solid`
Paints a solid object with a shadow

##### Options

* `$bar-color: #444`
* `$bar-text-color: #fff`
* `$bar-shadow: none`

#### `bar-hollow`
Paints a bordered object

##### Options

* `$bar-color: #444`
* `$bar-border-width: 1px`
* `$bar-border-style: solid`

## License
This project is licensed under the MIT [license](LICENSE).

