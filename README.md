On this project I coded two implementations of a product storage,
first a mock based app where a customer has some wines and is able to add more (I made it unavailable since I did not have time to integrate
both by reusing the components)
and a second one which is an api based app https://www.thecocktaildb.com/api.php, which is the on currently displayed when running the app
(I choosed this api because the other ones where either not working or did not have images available)

My priorities where according to the following:
- I studied hooks for the first time and (re)implemented the whole application based on hooks when adding the online api for a cocktail library
- Architecture wise I followed the container pattern;
- Finally I tried to stick to functional programming and make the components as reusable as possible taking the little time I had to put the app
together;

I did use some external library for a couple components and ramda as my main util

By having more time, I would have tried to make the UX better and the UI more appealing

API
https://www.thecocktaildb.com/api.php
https://www.thecocktaildb.com/api/json/v1/1/search.php?s=margarita // drinks by name
https://www.thecocktaildb.com/api/json/v1/1/filter.php?i=Gin // drinks with ingredient
https://www.thecocktaildb.com/api/json/v1/1/lookup.php?i=11007 // drink based on ID

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
