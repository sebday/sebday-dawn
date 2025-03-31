# Dawn

A highly functional [Ghost](https://github.com/TryGhost/Ghost) theme that adapts to the reader's preferences. Let them read, search, subscribe, navigate, and more with ease.

**Demo: https://dawn.ghost.io**

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/dawn.zip`, which you can then upload to your site.

```bash
yarn zip
```
