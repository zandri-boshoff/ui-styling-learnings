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