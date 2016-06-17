# Ihor Zenich HTML/CSS/JS codestyle

Based on „Google's HTML Style Guide“, „SMACSS“, „CSS Guidelines by Harry Roberts“.
In short:

# HTML
## Formatting Rules
1. [NO TABS, 2 space indent](https://github.com/ideus-team/guidelines/blob/master/frontend/tabs.md)
2. lowercase
3. Double quotes
4. New line for everything
5. Omit the protocol from embedded resources.


# CSS
## Formatting Rules
1. NO TABS, 2 space indent
2. Multiple lines, groped by CSSComb with zen-coding declaration order
3. Single quotes
4. Variables should defined withing each block.
5. Use calc/variables for values that are dependent on other values.
6. Use Sass capabilities: `&__el`,  `@include i-abstractBlock`, etc.

## Naming Conversions
We use BEM CSS in [Harry Roberts](http://cssguidelin.es/#bem-like-naming) style with camelCase syntax and default `b-` prefix (for namespace reason).


# JS
## Formatting Rules
1. NO TABS, 2 space indent
2. Always use only `js-`classnames in JS! JS namespace has nothing at all to do with css.

## Naming Conversions
We use camelCase.

P.S.
Be consistent.
