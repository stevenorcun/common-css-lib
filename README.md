The library is for all the common styles that will be used in all micro frontend projects.

Example of use:

```javascript
npm i @altnativ/common-styles
```

Inside the the style.scss of the micro-frontend, import the package

```scss
@import "@altnativ/common-styles";
```

We can now use the classes defined in the index.scss

```scss
@import "./assets/scss/colors";

.btn-primary {
  color: $color-darkblue;
}
.btn-danger {
  color: $color-rose;
}
```

App.tsx file of the micro-frontend we can use them :

```jsx
<div className="container">
  <button className="btn-primary">Primray</button>
  <button className="btn-danger">Danger</button>
</div>
```
