# Tooltip UI component by Custom Elements

[![npm version](https://badge.fury.io/js/%40saekitominaga%2Fcustomelements-tooltip.svg)](https://badge.fury.io/js/%40saekitominaga%2Fcustomelements-tooltip)

Implement tooltip UI component by Custom Elements.

## Demo

- [Demo page](https://saekitominaga.github.io/customelements-tooltip/demo.html)

## Examples

```HTML
<x-tooltip
  open=""
  close-text="Close"
  close-src="/assets/tooltip-close.svg"
>
</x-tooltip>
```

## Attributes

<dl>
<dt><code>open</code> [optional]</dt>
<dd>Whether the tooltip are visible.</dd>
<dt><code>close-text</code> [optional]</dt>
<dd>The text of the close button in the tooltip (Image alternative text). The default value is `Close`.</dd>
<dt><code>close-src</code> [optional]</dt>
<dd>The address of the image resource for the close button in the tooltip. The default is a gray x button (SVG format).</dd>
</dl>
