# qake-contract-testing-ajv


## commands:

### installation:

- npm i

### running tests:

- npm run test

### FIX TESTS:
now we use the jsonSchema this way ('type' is "string") because we want the tests to be broken!
to fix them open the following path: cypress\fixtures\jsonSchema.json and change line 24 'type' to "integer".
