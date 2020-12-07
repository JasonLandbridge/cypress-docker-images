<!-- WARNING: this file was autogenerated by generate-base-image.js -->
# cypress/base:12.18.4

A Docker image with all dependencies pre-installed.
Just add your NPM packages (including Cypress) and run the tests.
See [Cypress Docker docs](https://on.cypress.io/docker) and
[Cypress CI guide](https://on.cypress.io/ci).

## Example

Sample Dockerfile

```
FROM cypress/base:12.18.4
RUN npm install --save-dev cypress
RUN $(npm bin)/cypress verify
RUN $(npm bin)/cypress run
```

Versions

```
node version:    v12.18.4
npm version:     6.14.8
yarn version:    1.22.10
debian version:  10.5
user:            root
```