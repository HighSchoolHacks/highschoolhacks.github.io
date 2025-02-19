Tech Retreat
===============
[![Circle CI](https://circleci.com/gh/TechRetreat/techretreat.github.io.svg?style=svg)](https://circleci.com/gh/TechRetreat/techretreat.github.io)

A website for Tech Retreat.

Tech Retreat brings together passionate high school students for a one-day event held in the heart of Canada's technology hub. Hear from seasoned speakers and students in the industry. Learn and collaborate with like-minded peers to create something amazing.

## Editing
- **Pages:** Edit the mustache templates in `/pages` and rerender with `grunt mustache_html`
- **Styles:** Edit the sass in `/scss` and render with `grunt sass` and then `grunt autoprefixer`
- **Javascript**: Edit the ES6 js in `/src` and render with `grunt babel`

## Development Environment
Ensure you have npm installed, and that you've cloned this repo.

If you don't have npm, download [Node.js and npm](https://nodejs.org/).

Then, open your terminal and `cd` into this repo's directory:
```
$ npm install
```
This will install all dependencies. Namely `babel` so we can use all that sweet ES6 syntax!

To run the server:
```
$ grunt
```

Then navigate to `localhost:8000` in your browser.

## Contribution
Please submit pull requests for changes you make, and ping the team on Slack.
To organize branches please prefix them with `feature/` or `patch/` depending on the scope of the change.
