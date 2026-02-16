# css-borders

Functional CSS for borders

## Filesize

| File | Size |
|------|------|
| `dist/borders.css` | 1499 bytes |
| `dist/borders.min.css` | 1105 bytes (203 Gzipped) |

## Install

```sh
npm install css-borders
```

## Usage

### Import

```css
@import "css-borders";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-borders/dist/borders.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-borders/dist/borders.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ba` | `border-style: solid;   border-width: 1px;` |
| `.bt` | `border-top-style: solid;   border-top-width: 1px;` |
| `.br` | `border-right-style: solid;   border-right-width: 1px;` |
| `.bb` | `border-bottom-style: solid;   border-bottom-width: 1px;` |
| `.bl` | `border-left-style: solid;   border-left-width: 1px;` |
| `.ba-s` | `border-style: solid;     border-width: 1px;` |
| `.bt-s` | `border-top-style: solid;     border-top-width: 1px;` |
| `.br-s` | `border-right-style: solid;     border-right-width: 1px;` |
| `.bb-s` | `border-bottom-style: solid;     border-bottom-width: 1px;` |
| `.bl-s` | `border-left-style: solid;     border-left-width: 1px;` |
| `.ba-m` | `border-style: solid;     border-width: 1px;` |
| `.bt-m` | `border-top-style: solid;     border-top-width: 1px;` |
| `.br-m` | `border-right-style: solid;     border-right-width: 1px;` |
| `.bb-m` | `border-bottom-style: solid;     border-bottom-width: 1px;` |
| `.bl-m` | `border-left-style: solid;     border-left-width: 1px;` |
| `.ba-l` | `border-style: solid;     border-width: 1px;` |
| `.bt-l` | `border-top-style: solid;     border-top-width: 1px;` |
| `.br-l` | `border-right-style: solid;     border-right-width: 1px;` |
| `.bb-l` | `border-bottom-style: solid;     border-bottom-width: 1px;` |
| `.bl-l` | `border-left-style: solid;     border-left-width: 1px;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ba-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/borders.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/borders.css` — formatted
- `dist/borders.min.css` — minified

## License

MIT
