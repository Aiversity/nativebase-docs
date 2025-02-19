---
id: tooltip
title: Tooltip
---

A tooltip is a brief, informative message that appears when a user interacts with an element. Tooltips are usually initiated in one of two ways: through a mouse-hover gesture or through a keyboard-hover gesture.

## Import

```jsx
import { Tooltip } from 'native-base';
```

## Examples

### Basic

```ComponentSnackPlayer path=composites,Tooltip,Basic.tsx

```

### Positions

```ComponentSnackPlayer path=composites,Tooltip,TooltipPositions.tsx

```

### Customizing tooltip

Tooltip is a wrapper around [Box](box.md). So, it also accepts all the [Box](box.md#props) props.

```ComponentSnackPlayer path=composites,Tooltip,CustomTooltip.tsx

```

:::tip Tip
You can pass custom backgroundColor using `bg` or `backgroundColor`, `borderColor` and `borderWidth` to Tooltip.
:::

## Props

```ComponentPropTable path=composites,Tooltip,Tooltip.tsx

```
