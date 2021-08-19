# @the-innovation-circuit/theme

[Theme UI](https://theme-ui.com) theme for [The Innovation Circuit](http://innovationcircuit.co/). Forked from [Hack Club](https://hackclub.com)'s [theme](https://theme.hackclub.com).

```bash
yarn add @the-innovation-circuit/theme
# npm i @the-innovation-circuit/theme
```

Check out theme: [**theme.innovationcircuit.co**](http://theme.innovationcircuit.co/)

## Usage

```js
import { ThemeProvider } from 'theme-ui'
import theme from '@the-innovation-circuit/theme'

export default ({ children }) => (
  <ThemeProvider theme={theme}>{children}</ThemeProvider>
)
```

### Fonts

This package also bundles a CSS file that includes our webfonts: `fonts.css`.
To use, just import straight from the package:

```js
import '@the-innovation-circuit/theme/fonts/fonts.css'
```

(In a Next.js project, [place](https://nextjs.org/docs/basic-features/built-in-css-support) in the `pages/_app.js` file.)

MIT License
