# Google Books Search Engine

For this challenge you will be creating a rudimentary search engine that consumes the Google Books API. This is a test of basic frontend proficiency that tests JavaScript knowledge, http requests, and css layouts.

## Instructions
- Fork this repository and complete the challenge according to the specifications below.
- Once finished, open a pull request with your changes, and notify us via email that your code has been submitted.

## Prerequisites
- [Node.js](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/en/docs/install) or npm

## Environment
- `yarn start`
    - Starts the parcel development server and watches for changes. This will compile `/src` to `/dist` and serve the contents on http://localhost:1234.

## Specifications
- Research the [Google Books Volume API](https://developers.google.com/books/docs/v1/reference/volumes) to determine how to search for books given a query. You will need to create an [API key](https://developers.google.com/books/docs/v1/using#APIKey).
- Build a basic search engine for Google Books. There should be a search bar to input a query that will be be passed as an argument to the Google Books API. The results should be rendered in the results area. You must include these fields (if available for the record):
  - Cover image
  - Title
  - Subtitle
  - Authors
- Additionally, each result should somehow provide a link to its respective Google Books page. Look at a Google Books entry on Google Books, and see which parameter might help you.
- Each subsequent query should append its results to the results area.
- There must be no duplicates (by Google Books id).
- The results should be visually appealing, styled logically, and fully responsive for mobile devices.
- While you may use the three function stubs provided in `main.js`, this challenge will require you to write some code outside of them.


## Notes
- While not necessary, you may use React or another library/framework to complete this project.
- You are encouraged to use ES6+ JavaScript. Babel is included in this project, and any imported JavaScript will automatically be transpiled when `yarn start` is run.
- You may use jQuery or other dependencies, but you should justify your dependencies in your PR.
