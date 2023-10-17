# sass-between

Sass library for fluid sizing between breakpoints

DEPRECATED: Natively supported by css viewport-relative units and clamp() these days.

## Usage

- npm install `sass-between`
- `@import "sass-between";` or
- copy `dist/_between.scss` to somewhere else to import.
- add `--load-path=node_modules` to sass command line, or equivalent bundler config.
- Replace default variables:

```
$between-min: 360px;
$between-max: 1200px;
$between-dimension: width;
```

## References

- [Between the Lines](https://css-tricks.com/between-the-lines/)
- [The math of CSS locks](https://fvsch.com/code/css-locks/)
- [Eduardo Bouças / Viewport sized typography with minimum and maximum sizes](https://eduardoboucas.com/blog/2015/06/18/viewport-sized-typography-with-minimum-and-maximum-sizes.html)
- [Precise control over responsive typography](https://madebymike.com.au/writing/precise-control-responsive-typography/)
- [Flexible typography with CSS locks](https://blog.typekit.com/2016/08/17/flexible-typography-with-css-locks/)
- [Fluid Responsive Typography With CSS Poly Fluid Sizing](https://www.smashingmagazine.com/2017/05/fluid-responsive-typography-css-poly-fluid-sizing/)
- https://github.com/unionco/scss-slope-calc
