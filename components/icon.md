---
description: <Icon> component
---

# Icon

## Usage

Icons are available via two ways in the Design System:

* `name` prop in the `<Icon>` component (e.g. `<Icon name="edit" />`)
* named component (e.g. `<EditIcon />`)

```javascript
import { Icon, EditIcon } from "@firehydrant/design-system";

// <Icon> component with `name` prop
<Icon name="edit" />

// <EditIcon> component
<EditIcon />
```

### Props

| prop    | Description                                                                                                                                               | Default        |
| ------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- |
| `name`  | <p>Name of the desired icon.</p><p><code>string</code></p>                                                                                                | `info`         |
| `color` | <p>Desired color of the icon.</p><p><code>&#x3C;</code><a href="../fundamentals/colors.md"><code>any valid theme color value</code></a><code>></code></p> | `currentColor` |

## Icon list

{% embed url="https://main--607731addb01d30021caeac2.chromatic.com/iframe.html?id=components-icon--all-icons&viewMode=story" %}
All icons from Storybook
{% endembed %}
