The library is for all the common styles that will be used in all micro frontend projects.

Inside the build folder there is all the compiled sass from the entry point src/index.scss
To use this complied style (all the classes defined etc...) we just need to import it in others projects.

Example of use:

```javascript
npm i @altnativ/common-styles
```

then inside the style.scss of the micro-frontend, just import the package (as the "main" value of the lib is "dist/index.scss" it will
point to the compilied scss) :

```scss
@import "@altnativ/common-styles";
```
