# Contract Testing using AJV 💻

[![jest](https://img.shields.io/badge/cypress-lightgray?style=flat&logo=cypress)](https://github.com/cypress-io/cypress)
[![npm](https://shields.io/badge/npm-%5E8.x.x-red?logo=npm&style=plastic)](https://www.npmjs.com/)

This project is an Contract Test example using JavaScript, [Jest](https://jestjs.io/docs/en/getting-started) and [SuperTest](https://github.com/visionmedia/supertest).
## commands:

### installation:

- npm i

### running tests:

- npm run test

### FIX TESTS:
now we use the jsonSchema this way ('type' is "string") because we want the tests to be broken!
to fix them open the following path: cypress\fixtures\jsonSchema.json and change line 24 'type' to "integer".
