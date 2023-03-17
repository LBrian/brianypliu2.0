## Installation

The repo is scaffolded under Node `16.19.1` so ensure you have the right version to avoid package dependency errors during installation. You can simply install the right node version using `nvm`

```
nvm i 16
nvm use 16
```

```
node -v
v16.19.1
```

install `pnpm`

```
curl -fsSL https://get.pnpm.io/install.sh | sh -
```

## Run the application locally

### `pnpm dev`

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Run unit test and e2e test

### `pnpm test`

Launches the test runner `Jest` in the interactive watch mode.

### `pnpm e2e`

Lunches `Playwright` e2e test and local web server to test against it. Test result will be output in the `playwright-report` folder.

## Build the production application

### `pnpm build`

Builds the app for production to the `build` folder.
