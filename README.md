API
Framework from scratch for API testing
Requirements

1. Node version 14
2. npm installed
Setup

1. git clone git@github.com:AnastasiaHrytsenko/week11-API.git
2. npm i
How to run all tests

npx playwright test --headed --workers 1

How to run a single test file

npx playwright test --headed --workers 1 tests/settings/general.spec.js

How to run a single test

Same a signle file, but you need to add .only to the test you wanna run test.only(.....

Notes: You can remove --headed if you don't need to see execution

Learn more about Playwright at https://playwright.dev/
