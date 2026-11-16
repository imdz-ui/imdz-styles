# @imdz/styles

The imdz design tokens (`src/tokens.css`), fonts (`src/fonts.css` and
`fonts/`) and the CSS of every component (`src/<component>.module.css`), written once and shared by
[`@imdz/react`](https://www.npmjs.com/package/@imdz/react) and
`@imdz/web-components`. Each library compiles this CSS into its own build, so
you don't need to install this package yourself.

The tokens are plain CSS variables (`--imdz-primary`, `--imdz-radius`…). To use
them in your own styles:

```css
@import "@imdz/styles/tokens.css";
```
