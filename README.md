<p align="center">
  <a href="https://biomatic-ui.com">
  	<img width=15% src="https://raw.githubusercontent.com/BioMaRu/biomatic/readme-resource/readme-images/logo.png">
  </a>
</p>

<h1 align="center">Biomatic UI</h1>
<p align="center">A Flexible Atomic-Focused CSS Framework</p>

<div align="center">
  
  <a href="https://npmjs.org/package/biomatic">
    <img src="https://img.shields.io/npm/v/biomatic.svg?style=flat-square"
      alt="NPM version" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/gzip size-34.7kb-brightgreen.svg?style=flat-square"
      alt="Gzip size" />
  </a>
  <a href="https://github.com/BioMaRu/biomatic/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square"
      alt="License" />
  </a>
</div>

<div align="center">
  <h3>
    <a href="https://biomatic-ui.com">
      Website
    </a>
    <span> &nbsp;|&nbsp; </span>
    <a href="https://biomatic-ui.com/document/introduction">
      Document
    </a>
  </h3>
</div>

## Table of Content
- [Features](#features)
- [Installation](#installation)
- [Configuration](#configuration)
- [License](#license)

## Features
- __atomic-focus:__ craft anythings you need with very flexible atomic class
- __battery-included:__ basic components included for rapid UI development
- __clean responsive grid:__ simple and clean grid layout using css grid
- __carefully naming:__ readable and predictable class name
- __configurable:__ config and build to match what you need 
- __pure css:__ no javascript required
- __fun:__ yes, very fun to use

## Installation
You can [download](https://github.com/BioMaRu/biomatic/releases/download/v0.1.2/biomatic.full.min.css.zip) the latest complied version of Biomatic and link to your project using
```html
<link href="/path/to/biomatic.full.min.css" rel="stylesheet">
```

Or install using NPM or Yarn
```shell
npm install biomatic
```

```shell
yarn add biomatic
```

## Configuration
You can configure things such as Color, Spacing, Breakpoint, or Add/Remove/Change value to Atomic Class to match your design or branding.

All configurations located in config.scss
```scss
/*==================================== 
  Main / Branding Color
======================================*/
$color-primary:     hsl(206, 100%, 56%);
$color-primary-900: hsl(206, 100%, 18%);
$color-primary-800: hsl(206, 100%, 27%);
$color-primary-700: hsl(206, 100%, 35%);
$color-primary-600: hsl(206, 100%, 45%);
$color-primary-500: hsl(206, 100%, 56%);
$color-primary-400: hsl(206, 100%, 66%);
$color-primary-300: hsl(206, 100%, 79%);
$color-primary-200: hsl(206, 100%, 87%);
$color-primary-100: hsl(206, 100%, 95%);

$color-accent:     hsl(350, 100%, 60%);
$color-accent-900: hsl(350, 100%, 20%);
$color-accent-800: hsl(350, 100%, 30%);
$color-accent-700: hsl(350, 100%, 40%);
$color-accent-600: hsl(350, 100%, 50%);
$color-accent-500: hsl(350, 100%, 60%);
$color-accent-400: hsl(350, 100%, 70%);
$color-accent-300: hsl(350, 100%, 80%);
$color-accent-200: hsl(350, 100%, 90%);
$color-accent-100: hsl(350, 100%, 95%);

$color-neutral:     hsl(213, 30%, 80%);
$color-neutral-900: hsl(213, 30%, 18%);
$color-neutral-800: hsl(213, 30%, 27%);
$color-neutral-700: hsl(213, 30%, 35%);
$color-neutral-700: hsl(213, 30%, 58%);
$color-neutral-600: hsl(213, 30%, 68%);
$color-neutral-500: hsl(213, 30%, 80%);
$color-neutral-400: hsl(213, 30%, 87%);
$color-neutral-300: hsl(213, 30%, 92%);
$color-neutral-200: hsl(213, 30%, 95%);
$color-neutral-100: hsl(213, 30%, 98%);

/*==================================== 
  Semantic Color
======================================*/
$color-positive: hsl(150, 80%, 45%);
$color-warning: hsl(40, 90%, 60%);
$color-info:    hsl(200, 100%, 65%);
$color-negative:   hsl(0, 100%, 65%);

/*==================================== 
  Gray Scale Color
======================================*/
$color-white: hsl(0, 255%, 100%);
$color-gray: hsla(0, 0%, 90%, 0.8);
$color-dark: hsla(231, 10%, 25%, 0.9);
$color-black: hsl(0, 0%, 0%);

/*==================================== 
  Responsive Breakpoint
======================================*/
$breakpoint-sm: 770px;
$breakpoint-md: 900px;
$breakpoint-lg: 1200px;

/*==================================== 
  Default Font Family
======================================*/
$font-primary: -apple-system, system-ui, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", sans-serif;
```

```scss
/*==================================== 
  Mapping Value
======================================*/

//  Value for Spacing -> Margin, Padding Top, Bottom, Left, Right, Width, Height
$pixel-value: (
  '0px': 0px,
  '1px': 1px,
  '2px': 2px,
  '4px': 4px,
  '8px': 8px,
  '12px': 12px,
  '16px': 16px,
  '24px': 24px,
  '32px': 32px,
  '48px': 48px,
  '64px': 64px,
  '128px': 128px,
  '256px': 256px,
  '512px': 512px,
  '50pct': 50%,
  'at': auto
);

// Value for Border Radius 
$border-radius-value: (
  '0px': 0px,
  '1px': 1px,
  '2px': 2px,
  '3px': 3px,
  '4px': 4px,
  '8px': 8px,
  '12px': 12px,
  '16px': 16px,
  '24px': 24px,
  '32px': 32px,
  '48px': 48px,
  '64px': 64px,
  '128px': 128px,
  '256px': 256px,
  '512px': 512px,
  '50pct': 50%,
  'max': 9999px
);
 
// Percentage Value for Width, Height
$percentage-value: (
  '10pct': 10%,
  '20pct': 20%,
  '30pct': 30%,
  '40pct': 40%,
  '50pct': 50%,
  '60pct': 60%,
  '70pct': 70%,
  '80pct': 80%,
  '90pct': 90%,
  '100pct': 100%,
  'at': auto
);

// Color Value for Color, Background Color, Border Color
$color-value: (
  'primary': $color-primary,
  'primary-900': $color-primary-900,
  'primary-800': $color-primary-800,
  'primary-700': $color-primary-700,
  'primary-600': $color-primary-600,
  'primary-500': $color-primary-500,
  'primary-400': $color-primary-400,
  'primary-300': $color-primary-300,
  'primary-200': $color-primary-200,
  'primary-100': $color-primary-100,

  'accent': $color-accent,
  'accent-900': $color-accent-900,
  'accent-800': $color-accent-800,
  'accent-700': $color-accent-700,
  'accent-600': $color-accent-600,
  'accent-500': $color-accent-500,
  'accent-400': $color-accent-400,
  'accent-300': $color-accent-300,
  'accent-200': $color-accent-200,
  'accent-100': $color-accent-100,

  'neutral': $color-neutral,
  'neutral-900': $color-neutral-900,
  'neutral-800': $color-neutral-800,
  'neutral-700': $color-neutral-700,
  'neutral-600': $color-neutral-600,
  'neutral-500': $color-neutral-500,
  'neutral-400': $color-neutral-400,
  'neutral-300': $color-neutral-300,
  'neutral-200': $color-neutral-200,
  'neutral-100': $color-neutral-100,
  
  'positive': $color-positive,
  'warning': $color-warning,
  'info': $color-info,
  'negative': $color-negative,
  
  'white': $color-white,
  'gray': $color-gray,
  'dark': $color-dark,
  'black': $color-black,

  'tpr': transparent
);

// Breakpoint
$breakpoints: (
  'sm': $breakpoint-sm,
  'md': $breakpoint-md,
  'lg': $breakpoint-lg
);
```

## License
Code copyright 2017 Theerapong Laowrungrat. Code released under the <a href="https://github.com/BioMaRu/biomatic/blob/master/LICENSE">MIT license.</a>
