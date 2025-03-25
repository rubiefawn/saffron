# 📐 saffron.css

Useful CSS variables and reasonable defaults, based on √2.

## Building

```sh
$ sass src/saffron.scss build/saffron.css --no-source-map --style=compressed
```

## Regarding Utility Classes

There are utility classes for margin and padding, as well as flex layout (similar to [almonk/pylon](https://github.com/almonk/pylon)) that are not included by default. To enable them, simply uncomment `@use 'space';` and/or `@use 'stack';` in `src/saffron.scss`.

Instead of using the margin and padding utility classes, prefer using the variables directly instead, applied to your own CSS classes as needed.

Instead of using the stack utility classes, prefer learning how CSS grid and flex layouts work and use those directly instead.
