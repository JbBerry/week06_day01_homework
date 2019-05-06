## Part 2
#### Answer the following questions:
######  1. Where do we directly access an element from the DOM in our React application?
`index.html` has a 'root' div which is appended to by `index.js`.
######  2. From looking at the code, what do you think might be the difference between the components in the `containers` and `components` directories?
containers contain the components when they are attached to the DOM and rendered
######  3. What is the responsibility of the `ReleasesBox` component?
`ReleasesBox.js` contains the information to be rendered within its state. It is also the `<div>` that contains the components when attached to the DOM.
######  3. What is the responsibility of the `MovieList` component?
`MovieList.js` is passed its prop from `ReleasesBox.js` it takes an array of Movie objects and produces an unordered list of `MovieItem`s.
######  4. What is the responsibility of the `MovieItem` component?
`MovieItem.js` is passed its prop from `MovieList.js` it takes a movie object and produces a list item with a movie title and a url.
