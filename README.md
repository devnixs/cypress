# Cypress
Cypress browsers with npm install already run

Very simple docker file that speeds up my tests.

```
FROM cypress/browsers:chrome65-ff57
RUN npm i cypress
```
