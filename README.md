# Trillo

This is an advanced CSS and Sass project that uses Flexbox.

### Planning/ Execution:
1. Global styles/ resets/ layouts
2. Header

### Advanced CSS and Sass Concepts used:
1. :root selector 
[Read More About the Root Selector](https://css-tricks.com/almanac/selectors/r/root/)

2. FlexBox

3. SVGs -- scalable vector graphs
SVGs are preferred since they are easily to manipulate and have better support than iconfonts.

###  Notes
FlexBox Definition and Terms:
1. Flex
Instead of writing flex-grow, flex-basis, flex-shrink you can simply write flex where the first item is flex-grow,
the second if flex-shrink, and the final is flex-basis. 
```
/* this */
flex: 1 100px;

/* is the same as */
flex-grow: 1;
flex-basis: 100px;

/* and it leaves the flex-shrink property alone, which would be */
flex-shrink: inherit; /* defaults to 1 */
```


### Final Product:

**Desktop**

<!-- ![](project-large.jpg) -->

**Mobile**

<!-- ![](project-small.jpg) -->

#### Future Developers:
`npm install`

`live-server` to run live server

`npm start` to compile sass into css && watch for changes

ENJOY!