# 📐 saffron.css

Simple CSS styles based on √2.

## Build

```sh
$ sass src/saffron.scss build/saffron.css --no-source-map --style=compressed
```

# Regarding fonts

Saffron applies fonts according to the following css variables: `--font-serif`, `--font-sans-serif`, `--font-display`, `--font-monospace`, and `--font-fantasy`. These fonts have defaults set, but these defaults are not provided by Saffron. Either override the variables, or include the default fonts in a separate style sheet. This is done so that fonts that aren't used on a page don't need to be loaded, as well as for easy theming.
