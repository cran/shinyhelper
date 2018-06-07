# shinyhelper 0.2.0

Welcome to shinyhelper v0.2.0 - this is an improved version on the original package, with greater freedom and ease for you to customise your app UI. 

**New Features:**

* dedicated `icon_colour` argument to `helper()` - no need to use `style = "color = ...;"` any more
* set size of each help page individually with the `size` argument to `helper()` - no more named lists!
* use a file name of your choice for your markdown help pages - no longer need to have the same as the shiny.tag input and output IDs
* new `shinyhelperDemo()` function, to run a demo app that comes installed with the package

**Deprecated Features:**

* the `sizes` and `default_size` arguments to `observe_helpers()` have been deprecated. They're still there, but will give a warning message if you try to use them.

I've also improved the documentation in the man pages.

### shinyhelper 0.1.1.9003

New features:

* can set sizes of help pages in `helper`, not named list in `observe_helpers()`
* can set custom filename for help pages - no longer need to use inputId and outputId although that's still the default.

Deprecated features:

* `sizes` and `default_size` arguments to `observe_helpers()`

### shinyhelper 0.1.1.9002

New features:

* example app installed with package
* better documentation of functions
* dedicated function `shinyhelperDemo` to run example app

### shinyhelper 0.1.1.9000

New features:

* Set colour of help icon with dedicated `colour` parameter.

# shinyhelper 0.1.1

This is the first version of the package.
