[Root Ventures](root.vc) has a custom video conferencing app built on the [Daily](daily.co) API. You can use this on your own if you like. Fork the repo and modify to your heart's content.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/rootvc/meet)

## Available Scripts

In the project directory, you can run:

### `npm install`

To install dependencies.

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Configuration

### Brand Styles

Edit `src/brand.css` to add your custom color scheme.

### Brand Marks

 - `public/favicon.ico`
 - `public/logo192.png`
 - `public/logo512.png`
 - `public/logo-header.png`
 - `src/logo.png`

### Environment Variables

Learn about environment variables on Netlify: https://docs.netlify.com/configure-builds/environment-variables/#declare-variables

`DAILY_API_KEY` = API key for [daily.co](daily.co) API

## Deployment

Deployment requires a [Netlify](netlify.com) account.

`netlify deploy`

Our app deploys with continuous [deployment hooks](https://docs.netlify.com/site-deploys/create-deploys/#drag-and-drop).

## References

Daily.co API Docs: https://docs.daily.co/reference

This app was created with create-react-app. You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started). (It has not been ejected. If you don't know what that means, either read the docs or don't worry about it.)

To learn React, check out the [React documentation](https://reactjs.org/).
