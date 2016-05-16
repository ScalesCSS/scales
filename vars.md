# Scales Variables
Scales comes with _a lot_ of variables so you can customize the defaults easily. I have organized them into groups below in the order that the files are imported in Scales. For more details, see the README file in the particular Scales repo.

## The Variables

### The Scales Namespace Variable

All Scales patterns expose the `$scales-namespace` variable.

`$scales-namespace` accepts a string that will prefix all Scales classes. The default value is `null`.

### _reset.scss
* `$selection-bg-color`
* `$selection-text-color`

### _typography.scss
* `$base-text-color`
* `$heading-color`
* `$text-margins`
* `$heading-margins`
* `$measure`
* `$narrow-measure`
* `$code-block-padding`
* `$code-block-margins`
* `$code-block-bg-color`
* `$code-block-text-color`
* `$pre-wordwrap` - Set to true to make text in a code block wrap to new lines when it reaches the bounds of the container.
* `$monospaced-font-stack`
* `$base-font-stack`
* `$heading-font-stack`
* `$heading-font-weight`
* `$base-font-size`
* `$base-line-height`
* `$lede-font-size`
* `$h1-size`
* `$h2-size`
* `$h3-size`
* `$h4-size`
* `$h5-size`
* `$h6-size`

### _blockquotes.scss
* `$source-prefix` - Character prefixing the source of a quote

### _forms.scss
* `$fieldset-padding`
* `$text-input-padding`
* `$text-input-border-width`
* `$text-input-border-style`
* `$text-input-border-color`
* `$text-input-border-radius`
* `$input-container-margin-bottom`
* `$input-disabled-border-color`
* `$input-disabled-background-color`
* `$input-disabled-text-color`
* `$input-readonly-border-color`
* `$input-readonly-background-color`
* `$input-readonly-text-color`

### _tables.scss
* `$table-padding-large`
* `$table-padding-medium`
* `$table-padding-small`
* `$table-border-width`
* `$table-border-style`
* `$table-border-color`
* `$table-stripe-color`

### _box.scss
* `$box-padding`
* `$box-padding-tiny`
* `$box-padding-small`
* `$box-padding-large`
* `$box-padding-huge`

### _horizontal-list.scss
* `$horizontal-list-delimiter`

### _vertical-list.scss
* `$vertical-list-delimiter`

### _media-object.scss
* `$media-gutter`
* `$media-gutter-tiny`
* `$media-gutter-small`
* `$media-gutter-large`
* `$media-gutter-huge`
* `$media-stacked-breakpoint`

### _flag.scss
* `$flag-gutter`
* `$flag-gutter-tiny`
* `$flag-gutter-small`
* `$flag-gutter-large`
* `$flag-gutter-huge`
* `$flag-stacked-breakpoint`

### _buttons.scss
* `$btn-background-color`
* `$btn-border-width`
* `$btn-border-color`
* `$btn-border-style`
* `$btn-text-color`
* `$btn-font`
* `$btn-padding`
* `$btn-disabled-opacity`

### _stats.scss
* `$stat-spacing` - space to the right of each stat

### _size.scss
* `$size-range-start` - Value of the first class
* `$size-range-end` - Value of the last class
* `$size-step-value` - Increment between values

### _spacing.scss
* `$space-s`
* `$space-m`
* `$space-l`
* `$space-h`
