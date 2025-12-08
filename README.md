# 📐 saffron.css

Useful CSS variables and reasonable defaults, based on √2.

## Building

```sh
$ sass src/saffron.scss build/saffron.css --no-source-map --style=compressed
```

## Regarding Flex Utility Classes

There are utility classes for flex layout (similar to [almonk/pylon](https://github.com/almonk/pylon)) that are not included by default. To enable them, simply uncomment `@use 'stack';` in `src/saffron.scss`. These are not enabled by default, since while they are very useful for rapid prototyping, flex layouts belong in proper CSS classes rather than in the HTML, and separation of concerns ought to be preserved when possible.
