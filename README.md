## Karma

Learn Karma.

## Dependencies

* karma - 6
* karma-jasmine - 4 - A Karma plugin - adapter for Jasmine testing framework.
* karma-chrome-launcher - 3 - A Karma plugin. Launcher for Chrome and Chrome Canary.

## Getting started

Issue `karma init` at the root of the project to generate `karma.config.js` file
and start editing it to your need.

## Running tests

To execute tests via npm scripts

    npm t

If you want to execute test and quit the browser using karma directly, you can set `singleRun`
in `karma.config.js` to be `true`.

    karma start

Setting `singleRun` to be `false` will result in Continuous Integration mode.
