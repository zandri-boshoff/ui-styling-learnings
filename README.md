# ui-styling-learnings

- [ui-styling-learnings](#ui-styling-learnings)
  - [Styled Components](#styled-components)

## Styled Components

- Tagged template literal: Calling a function and passing it as an argument a template string. For example:

```
const Button = styled.button`
    font-family: sans-serif
    `
```

- Custom JSX elements have to be pascal case ( starting with capital letter ).

## Grid vs  Flexbox
In general grid should be used for the layout of a large component like a landing page that consists of many sections. This is because grid is a horizontal and vertical layout concept. Flexbox on the other hand should in general be used when styling a one directional component like a header or footer component as Flexbox is a single direction layout concept.

## Relative vs absolute Styling

The reason why you should be using relative styling units instead of absolute units is to improve the accessability of your website. In other words if a user that is visually impared decides to increase his browser's font-size all of the components should scale based on that font size. If a developer used absolute styling units the elements on the screen won't scale.

The following is a guideline for which styling units to use when setting different styling properties of an element:
- font-size: rem ( relative to the font size of the root element)
- width: % 
- height: question urself "do i rly need to set height" if yes -> use a min-height
- padding/margin: rem or em, em for padding of buttons works well as the padding will increase as the font-size of the button icreases which means it will grow proportionally
- media-queries: em


