<br />

<p align="center">
  <h1 align="center">Flynt for Warp</h1>
</p>

<p align="center">Warm undertones in dark and light — <a href="https://flynt-theme.github.io/flynt">Flynt</a> for <a href="https://www.warp.dev">Warp</a> terminal.</p>

<br />

## Install

1. Copy the theme file for your preferred variant into `~/.warp/themes/`:

   **Dark**
   ```sh
   cp flynt-dark.yaml ~/.warp/themes/
   ```

   **Light**
   ```sh
   cp flynt-light.yaml ~/.warp/themes/
   ```

   > Create the directory first if it doesn't exist: `mkdir -p ~/.warp/themes`

2. Open Warp - Settings - Appearance - Theme and select **Flynt Dark** or **Flynt Light**.

## Variants

| Variant | File |
|---------|------|
| Dark | [`flynt-dark.yaml`](dist/flynt-dark.yaml) |
| Light | [`flynt-light.yaml`](dist/flynt-light.yaml) |

## Building from source

Themes are generated from [`theme.yaml.tmpl`](theme.yaml.tmpl) using [strike](https://github.com/flynt-theme/strike).

```sh
strike build theme.yaml.tmpl
```

## License

MIT - [Flynt Theme](https://github.com/flynt-theme)
