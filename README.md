# Font-awesome_SASS-variables
Simple SASS variables file for assign SASS variable to font awesome icons unicode.
>Font-awesome_SASS-variables currently based on font-awesome v4.6.3

## Usage

All variable name are based on original icon name.

### Classic font awesome CSS implementation
```sass
.foo
  &:before
    content: "\f004"
```
### Font-awesome_SASS-variables implementation
```sass
.foo
  &:before
    content: $fa-heart
```
