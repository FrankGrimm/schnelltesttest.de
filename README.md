# schnelltesttest.de

| ⚠️ WARNING: Please don't add tests via github PR!                                                              |
| -------------------------------------------------------------------------------------------------------------- |
| Instead, submit them as indicated [here](https://zerforschung.org/posts/schnelltesttest/#barcode-sammelalbum). |

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Updating the data

To load the new data from the PEI, use the `xlsx2all.py` script in `src/data`:

```
cd src/data
poetry install
poetry run python xlsx2all.py all.json
```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

**Note**: Website can only access the camera if they are server over https or on localhost. If you want to test this code on a seperate device, use `HTTPS=true yarn start`

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
