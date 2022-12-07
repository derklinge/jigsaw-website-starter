# Jigsaw Website Starter Project

## Features

### Web Fonts (self-hosted, served locally)

First, install a web font package using `npm`, e.g. @fontsource/barlow, like so:

```bash
npm install --save-dev @fontsource/barlow
```

Next you'll want to make sure the font and its variants are loaded.

Add an `@import` to the main stylesheet `main.css`, so the web font's CSS definitions
are parsed whenever (re-)generating the website:

```css
@import '@fontsource/barlow';
```

This will include the font's default variants and supported charsets.

Later on, you may want to tweak this to only include mandatory variants and/or
charsets to improve page load performance as well as improve build times.

## License

MIT
