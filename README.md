# blocktank-ui

### [blocktank.synonym.to](https://blocktank.synonym.to/)

Blocktank is an LSP that allows businesses, apps, or online platforms to integrate, automate, and monetize services from your Lightning node. This includes channel configuration, channel purchases, channel info and more.

The Blocktank Widget ([standalone](https://blocktank.synonym.to/) or [embeddable](https://widget.synonym.to/)) allows users to quickly configure and purchase Lightning channels with specific balances.

## Embed on any site

Recommended resolution for your embedded widget:

- width - `480px`
- height - `800px`

```html
<iframe
	style="margin: auto; min-width: 480px; min-height: 800px;"
	id="widget"
	src="https://widget.synonym.to/"
	seamless
></iframe>
```

## Environment Variables

Create `.env` file at the root folder.

Get information from `blocktank-client` mainnet **(true)** or testnet **(false)**:

```
REACT_APP_MAINNET=true
```

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `yarn build:mainnet` or `yarn build:testnet`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.\
The build is minified and the filenames include the hashes.
