<h1 align="center">Cypress to Playwright</h1>

## Prerequisites

- node >=16.0.0

## Install

```sh
npm install @tatotux/cypress-to-playwright -D
```

## Usage

```sh
npx @tatotux/cypress-to-playwright <cypress_directory>
```

## How it works

1. It will read all js files found in the <cypress_directory> folder.
2. It will convert each cypress command (supported ones) to the playwright version.
3. It will write the new files in the playwright folder at the same level as the indicated folder.
4. Follow the steps indicated in the script.

### Run tests

```sh
npm run test
```