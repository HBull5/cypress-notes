# cypress-notes

## Open Cypress GUI 

```command line
npx cypress open
```

* automatically builds directories

## Cypress.json file 

* Ignoring files 
```json
{
  "ignoreTestFiles": "**/examples/*" 
}
```

* Base URL 
```json
{
  "baseURL": "http://localhost:3000"
}
```

* You can specify several different vaues here read more in the documentation. 

## Conventions

*  All files must be named `{fileName}.spec.js` to be interpreted as a cypress test.

* To tell vscode to use cypress autocomplete/features add `/// <reference types="cypress" />` to the top of your test file.

* You can use `context()` or `describe()` to define the suite of tests you want to run. 
```javascript
describe('My Test Suite Title', () => { /* tests */ });
```

## Cypress API

* `cy.visit({ url })` directs cypress to a url

* `cy.beforeEach(() => {});` runs before each test

* `cy.beforeAll(() => {});` runs before all test(s) only once

* get
```javascript

```

* contains 
```javascript

```

* child
```javascript 

```
