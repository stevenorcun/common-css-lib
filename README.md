Sass library to share all common styles in all micro frontend projects.

Example of use

To use this styles defined in the library :

```scss
@import "./assets/scss/colors";

.btn-primary {
  color: $color-darkblue;
}
.btn-danger {
  color: $color-rose;
}
```

Fisrt install the lib :

```js
npm i @altnativ/common-styles
```

Inside the the style.scss of the micro-frontend, import the package :

```scss
@import "@altnativ/common-styles";
```

In the App.tsx file of the micro-frontend we can use them :

```jsx
<div className="container">
  <button className="btn-primary">Primray</button>
  <button className="btn-danger">Danger</button>
</div>
```

To use the common fonts of the lib, in the styles.scss of the mirco-frontend :

```scss
@import "@altnativ/common-styles/src/assets/scss/fonts";

body {
  font-family: $font-primary-default;
}
```
