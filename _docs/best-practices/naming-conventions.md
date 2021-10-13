---
title: Naming Conventions
description: Writing clear and consistent names for things
tags:
    - css
---

# {{ page.title }}

## General

-   Prefer descriptive names over of short names
-   Use abstract, reusable names instead of specific, single-use names

### Selectors

-   Avoid using IDs as Selectors
-   Avoid using data attributes as selectors

## Naming IDs

Use CamelCase for IDs. e.g. `#menuToggle`

## Naming CSS Classes

Use hyphen-delimited class names. e.g. `.page-header`

### Using BEM

-   Use [BEM](https://css-tricks.com/bem-101/) whenever possible
-   Use utility classes sparingly
-   Avoid nesting when possible

`.box__element--modifier`

#### Examples

**Box classes**

Targets the outermost element of a component for global styling

```SCSS
.card {}
```

**Element classes**

Targets parts within the component for global styling

```SCSS
.card__image {}
.card__title {}
.card__body {}
.card__button {}
```

**Modifier classes**

Used to make small situational changes to the component or parts of the component

```SCSS
.card--centered {}
.card__image--round {}
.card__button--large {}
```
