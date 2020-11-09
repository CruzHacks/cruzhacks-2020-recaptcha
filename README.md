# CruzHacks 2021 Firebase Functions Template

This is a repository for a template to deploy a firebase function. Use it whenever you are creating a new firebase function.

![cruzhacks-firebase-template](https://github.com/CruzHacks/cruzhacks-2021-function-template/workflows/cruzhacks-2021-function-template/badge.svg)

## Development

### Dependnecies
- Can be found inside `package.json` file. Installed using the following command: 
  - `yarn` or `yarn -i` or `yarn install` within the `/functions` directory

### Start

`yarn serve`

* Begin an emulator suite at `localhost:4000` with your function being served at `localhost:5000`. You can navigate the UI of the Emulator Suite to find the actual endpoint. 

### Test

This project uses [Jest](https://jestjs.io/). Run all tests via `yarn test`. 

### Environment Variables

Can be obtained by running `firebase functions:config:get > .runtimeconfig.json` within your `/functions` directory

## Request Schema

```shell
$ request schema goes here
```

## Response Schemas

### Successful Response Case #1

```json
{
    "response": "schema goes here"
}
```

### Failed Response Case #2
```json
{
  "response": "schema goes here"
}
```

### Failed Response Case #3

```json
{
  "response": "schema goes here"
}
```

## Technologies

- Firebase Functions
- NodeJS
- Jest
- Github Actions
- Prettier
- Eslint