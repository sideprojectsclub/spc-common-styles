# Side Projects Club Common Styles

This is a submodule of common SCSS between the Side Projects Club theme and the Side Projects Club Chapter theme, in order to make it easier to maintain the similar look between the two.

This submodule exists in the assets/scss directory of the themes. In assets/scss/main.scss, these partials should be included like so:

```
@include 'spc-common-styles/_common';

// Include the theme-specific styles after
```

Then the common styles and theme-specific styles will be compiled into one tidy CSS file in assets/css.