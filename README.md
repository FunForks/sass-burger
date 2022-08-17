# SASS Burger #

This repo is based on [scss-from-scratch](https://github.com/FunForks/scss-from-scratch) and [burger-menu](https://github.com/FunForks/burger-menu).

You can test the result [here](https://funforks.github.io/sass-burger).

It provides a SCSS version of a responsive hamburger menu.

Specifically:
* SCSS variables are set in [_variables.scss](src/scss/_variable.scss), rather than using CSS Custom Properties
* The `@media` queries for a desktop layout are defined in [_desktop.scss](src/scss/_desktop.scss)
* These two partials are imported into [main.scss](src/scss/main.scss), which defines the hamburger menu layout for narrow viewports.
* The `"scripts"` section of `package.json` is set up to deploy a custom `gh-pages` branch to GitHub.