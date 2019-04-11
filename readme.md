# Why
How do you opening an incognito window in Chrome using Cypress?

incognito windows are caused by passing the --incognito flag when spawning the browser

before:browser:launch

https://docs.cypress.io/api/plugins/browser-launch-api.html#Modify-args-based-on-browser

# Setup

Clone repo

`npm install`

`npm run cypress` OR `npx cypress open`

Select any example test to run.

Result... Chrome launch in incognito mode but... "Whoops we can't run your tests"
![Incognito](incognito.png?raw=true "Incognito")
