# SvgIcon



## Props
| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| children | node |  | Elements passed into the SVG Icon. |
| titleAccess | string |  | Provides a human-readable title for the element that contains it. https://www.w3.org/TR/SVG-access/#Equivalent |
| viewBox | string | '0 0 24 24' | Allows you to redefine what the coordinates without units mean inside an svg element. For example, if the SVG element is 500 (width) by 200 (height), and you pass viewBox="0 0 50 20", this means that the coordinates inside the svg will go from the top left corner (0,0) to bottom right (50,20) and each unit will be worth 10px. |

Any other properties supplied will be spread to the root element.
## Classes

You can overrides all the class names injected by Material-UI thanks to the `classes` property.
This property accepts the following keys:
- `svgIcon`

Have a look at [overriding with class names](/customization/overrides#overriding-with-class-names)
section for more detail.

If using the `overrides` key of the theme as documented
[here](/customization/themes#customizing-all-instances-of-a-component-type),
you need to use the following style sheet name: `MuiSvgIcon`.