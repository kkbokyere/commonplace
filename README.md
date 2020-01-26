# Common Place Q&A

## Introduction

A simple Q&A application built in [React](https://reactjs.org/), [Redux](https://redux.js.org/) and [Webpack](https://webpack.js.org/).

## Requirements

- [Node](https://nodejs.org/en/).
- [npm](https://www.npmjs.com/package/npm).

## Getting Started

**1. Clone Git Repo.**

```
git clone https://github.com/kkbokyere/commonplace.git
```

**2. Install Dependencies.**

Once that's all done, cd into the thought-machine-calendar directory and install the dependencies:

```
$ cd commonplace
$ cd web
$ yarn install
```

**4. Run Application.**

Once the node modules have all been installed and npm has done it's thing, that's it. To open up a local development environment, run:

```
$ yarn dev
```

Once the server is up and running, navigate to [localhost:3000](http://localhost:3000).

## Testing

[Jest](https://jestjs.io/) is testing platform used for the project. To run test use the following command:

```
$ yarn test
```

# Tools Used

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org)
- [NextJS](https://nextjs.org/)
- [SASS](https://sass-lang.com/)
- [Webpack](https://webpack.js.org/)
- [ESLint](https://eslint.org/)
- [Create React App](https://facebook.github.io/create-react-app)

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.

### `yarn build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

## Improvements

### Unit Testing
- Due to time, I didn't get much time to have complete code coverage on all components, actions and reducers.

- I would have possibly also added some E2E test using Cypress.
