# WebFont: Montserrat

The `webfont-montserrat` package simplifies the process of self-hosting the [Montserrat Font](https://fonts.google.com/specimen/Montserrat) for applications making use of Vanilla CSS or any framework such as Tailwind CSS.

</br>

## Getting Started

1. Install the package:

```bash
$ npm install -S webfont-montserrat
```

2. Import it into your main stylesheet:

```css
@import url('/node_modules/webfont-montserrat/dist/index.css');
```

3. Register it in your application:

```css
html {
  font-family: "Montserrat", sans-serif;
  font-size: 16px;
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  ...
}
```


3. Alternatively, if you're using Tailwind CSS:

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

@layer base {
  html {
    font-family: "Montserrat", sans-serif;
    font-size: 16px;
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    ...
  }
}
```





<br/>

## Built With

- CSS
- JavaScript





<br/>

## License

[MIT](https://choosealicense.com/licenses/mit/)





<br/>

## Acknowledgments

- [Google Fonts](https://fonts.google.com/specimen/Montserrat)
- [clean-css](https://github.com/clean-css/clean-css)





<br/>

## Deployment

1. Install dependencies:
```bash
$ npm install
```

2. Build the package:
```bash
$ npm start
```

3. Publish to `npm`:
```bash
$ npm publish
```