---
description: System color scale & categories
coverY: 0
---

# Colors

The system’s color scale has been created in collaboration with brand marketing.&#x20;

Brand colors serve most functions within FireHydrant, with status and accent colors assisting.

Accent colors are least commonly used, but can be applied decoratively.&#x20;

{% embed url="https://607731addb01d30021caeac2-utlitdwato.chromatic.com/iframe.html?args=&id=colors--page&viewMode=story" %}
Color palette from Storybook
{% endembed %}

## Developers

Generally speaking, you will not need to alter the given colors of any component.

However, access to the color tokens is necessary when inventing components not provided, or modifying existing ones.&#x20;

Color-aware [style props](https://zeroheight.com/63e3d0331/p/881236--colors/t/8233a9) allows for this kind of styling of components.

```javascript
import { Box } from "@firehydrant/design-system";

// dot notation => `theme.colors.purple[70]`
<Box color='purple.70' />

// style prop shorthand => `background='gray.10'`
<Box bg='gray.10' />

// camelCase any CSS property
<Box borderBottomColor='gray.10' />
```

### Style Props <a href="8233a9" id="8233a9"></a>

> Style props are a way to alter the style of a component by simply passing props to it. It helps to save time by providing helpful shorthand ways to style components.

_– Originally published on _[_Chakra UI's Style Props docs_](https://chakra-ui.com/docs/features/style-props)

Colors can be applied to any Design System component; please see the table below for style props affected by color.

| Prop                | CSS Property                | Theme Key |
| ------------------- | --------------------------- | --------- |
| `color`             | `color`                     | `colors`  |
| `bg, background`    | `background`                | `colors`  |
| `bgColor`           | `background-color`          | `colors`  |
| `borderColor`       | `border-color`              | `colors`  |
| `borderTopColor`    | `border-top-color`          | `colors`  |
| `borderRightColor`  | `border-right-color`        | `colors`  |
| `borderEndColor`    | `border-inline-end-color`   | `colors`  |
| `borderBottomColor` | `border-bottom-color`       | `colors`  |
| `borderLeftColor`   | `border-left-color`         | `colors`  |
| `borderStartColor`  | `border-inline-start-color` | `colors`  |
| `fill`              | `fill`                      | `colors`  |
| `stroke`            | `stroke`                    | `colors`  |

## Accessibility

| Criterion                                                                    | Technique                                                     | Description                                                                                                                                                              |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [1.4.1](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)            | [G14](https://www.w3.org/WAI/WCAG21/Techniques/general/G14)   | Ensure that information conveyed by color differences is also available in text                                                                                          |
| [1.4.1](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)            | [G111](https://www.w3.org/WAI/WCAG21/Techniques/general/G111) | Using color and pattern                                                                                                                                                  |
| [1.4.1](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)            | [G182](https://www.w3.org/WAI/WCAG21/Techniques/general/G182) | Ensure that additional visual cues are available when text color differences are used to convey information                                                              |
| [1.4.1](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)            | [G183](https://www.w3.org/WAI/WCAG21/Techniques/general/G183) | Use a contrast ratio of 3:1 with surrounding text and provide additional visual cues on hover for links or controls where color alone is used to identify them           |
| [1.4.1](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color)            | [G205](https://www.w3.org/WAI/WCAG21/Techniques/general/G205) | Include a text cue for colored form control labels                                                                                                                       |
| [1.4.11](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html) | [G207](https://www.w3.org/WAI/WCAG21/Techniques/general/G207) | Ensure that a contrast ratio of 3:1 is provided for icons                                                                                                                |
| [1.4.11](https://www.w3.org/WAI/WCAG21/Understanding/non-text-contrast.html) | [G209](https://www.w3.org/WAI/WCAG21/Techniques/general/G209) | Provide sufficient contrast at the boundaries between adjoining colors                                                                                                   |
| [1.4.3](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum)        | [G18](https://www.w3.org/WAI/WCAG21/Techniques/general/G18)   | Ensuring that a contrast ratio of **at least 4.5:1 **exists between text (and images of text) and background behind the text for **text smaller than 24px or 19px bold** |
| [1.4.3](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum)        | [G145](https://www.w3.org/WAI/WCAG21/Techniques/general/G145) | Ensure contrast ratio of **at least 3:1** exists between text (and images of text) and background behind the text for **text larger than 24px or 19px bold**             |
| [2.4.7](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible)           | [G195](https://www.w3.org/WAI/WCAG21/Techniques/general/G195) | Using an author-supplied, highly visible focus indicator                                                                                                                 |
