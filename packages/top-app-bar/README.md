# Top App Bar React

MDC React Top App Bar is a React component which uses MDC [MDC Top App Bar](https://github.com/material-components/material-components-web/tree/master/packages/mdc-top-app-bar)'s CSS and foundation JavaScript.

## Installation

```
npm install @material/react-top-app-bar
```

## Usage

## Props

Prop Name | Type | Description
--- | --- | ---
actionItems | Array | Accepts an array of elements that should be rendered to the opposite side of the title. Note that a single action item should also be passed as an array.
className | String | Classes to be applied to the root element.
title | String | The title of the Top App Bar.
navigationIcon | Element | Appears adjacent to the title. This acts as the main action of the Top App Bar.
short | n/a | Enables short variant.
shortCollapsed | n/a | Enables short collapsed variant.
prominent | n/a | Enables prominent variant.

> NOTE: As per design guidelines, prominent variant should not be used with short or short collapsed.

### Navigation Icon

The navigation icon can be a `<a>`, `<i>`, `<svg>`, `<image>`, `<span>`, etc.

```js
  <TopAppBar
    navigationIcon={<i className='material-icons'>menu</i>} />
```

If you decide to use a React Component please see [Integrating with Components](./../../docs/guidelines.md#integrating-with-components).

### Action Items

Similar to the [navigation icon](#navigation-icon), it can be `<a>`, `<i>`, `<svg>`, `<image>`, `<span>`, etc.

```js
  <TopAppBar
    actionItems={[<i className='material-icons'>bookmark</i>]} />
```

If you decide to use a React Component please see [Integrating with Components](./../../docs/guidelines.md#integrating-with-components).

> NOTE: `actionItems` prop is expecting an array of elements.

Please see [MDC Web Top App Bar Readme](https://github.com/material-components/material-components-web/tree/master/packages/mdc-top-app-bar) for more information.

## Sass Mixins

Sass mixins may be available to customize various aspects of the components. Please refer to the
MDC Web repository for more information on what mixins are available, and how to use them.

[Advanced Sass Mixins](https://github.com/material-components/material-components-web/blob/v0.34.1/packages/mdc-top-app-bar/README.md)