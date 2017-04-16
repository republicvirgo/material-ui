Avatar
======



Props
-----

| Name | Type | Default | Description |
|:-----|:-----|:--------|:------------|
| alt | string | '' | Used in combination with `src` or `srcSet` to provide an alt attribute for the rendered `img` element. |
| children | node |  | Used to render icon or text elements inside the Avatar. `src` and `alt` props will not be used and no `img` will be rendered by default.<br>This can be an element, or just a string. |
| className | string |  | The CSS class name of the root element. |
| component | union:&nbsp;string<br>&nbsp;func<br> | 'div' | The component used for the root node. Either a string to use a DOM element or a component. |
| sizes | string |  | The `sizes` attribute for the `img` element. |
| src | string |  | The `src` attribute for the `img` element. |
| srcSet | string |  | The `srcSet` attribute for the `img` element. |

Any other properties supplied will be spread to the root element.