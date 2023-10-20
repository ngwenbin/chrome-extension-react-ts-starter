# react-chrome-extension-ts-starter

It is a boilerplate for a Chrome Extension built with React, TypeScript and Parcel.

## This starter consists of the following parts

- Background script (vanilla TS)
- Content script (vanilla TS)
- Options page (React, Styled Components)
- Popup page (React, Styled Components)
- DevTools panel page (React, Styled Components)

_And, of course, the `./manifest.json` file describing its configuration._

## Environment

- Node.js >=12.0.0
- NPM >= 6.0.0

_Most probably it will work with earlier versions too but I didn't test it._

## Testing

`Jest` is included and ready for the vanilla TS parts. Testing for React is not included in order to keep the Jest config clean.

## Scripts

- `yarn dist` - build the extension into `./dist` folder
- `yarn lint` - ESLint for `.ts` and `.tsx` files
- `yarn test` - Jest unit tests
