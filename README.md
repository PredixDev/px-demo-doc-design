# px-demo-doc-design

The demo-doc module is the sass file we use to style our documentation demo pages seen on predix-ui.com(https://www.predix-ui.com/) 

## Dependencies

Predix UI's Buttons module depends on two other Px modules:

* [px-colors-design](https://github.com/PredixDev/px-colors-design)
* [px-defaults-design](https://github.com/PredixDev/px-defaults-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save px-demo-doc-design

Once installed, `@import` into your project's Sass file in its Component layer:

    @import "px-demo-doc-design/_component.demo-doc.scss";

## CSS Variables

These css variables are available:

    --px-demo-api-background-color
    --px-demo-component-background-color
    --px-demo-containers-border-color
    --px-demo-interactive-background-color
    --px-demo-properties-background-color
    --px-footer-background-color
    --px-footer-text-color
    --px-footer-text-color--hover
    --px-footer-text-color--pressed