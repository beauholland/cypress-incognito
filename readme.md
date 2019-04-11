# Why
How do you open an incognito window in Chrome using Cypress?

This repo includes an example using the plugin method using `'before:browser:launch'` see [\cypress\plugins\index.js](\cypress\plugins\index.js)


Incognito windows are launched by passing the --incognito flag when spawning the browser.

See doco here: 
https://docs.cypress.io/api/plugins/browser-launch-api.html#Modify-args-based-on-browser

# Problem 
Chrome is launched in incognito mode = good

Message "Whoops, we can't run your tests" = bad.

Why?

![Incognito](incognito.png?raw=true "Incognito")

# Setup / Run

Clone repo

`npm install`

`npm run cypress` OR `npx cypress open`

Select any example test to run.

Result... Chrome launch in incognito mode but... "Whoops we can't run your tests"
