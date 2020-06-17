# javascript-toolkit
List my of preferred tools to work on JavaScript-based application.

## Editor

- [Visual Studio Code](https://code.visualstudio.com/). I really like this free and reliable editor because it has the IntelliSense feature.
- [RunKit](https://runkit.com). 
RunKit notebooks are interactive javascript playgrounds connected to a complete node environment right in your browser. Every npm module pre-installed.
- [CodeSandbox](https://codesandbox.io/). The online code editor for Web.
- [Quill](https://quilljs.com/). Modern rich text editor built for compatibility and extensibility.

## Framework

### Front-end

- [GatsbyJS](https://www.gatsbyjs.org/)
- [NextJS](https://nextjs.org/)
- [Angular](https://angular.io/)

### Backend

- [Express: Fast, unopinionated, minimalist web framework for Node.js](http://expressjs.com)
- [hapi: Build powerful, scalable applications, with minimal overhead and full out-of-the-box functionality](https://hapi.dev/)
- [Koa: smaller, more expressive, and more robust foundation for web applications and APIs](https://koajs.com/)
- [Fastify: Fast and low overhead web framework](https://github.com/fastify/fastify). Use this framework if the requirements are expecting the server to handle more significant number of request. See [the benchmark](https://github.com/fastify/benchmarks).

### CLI-related tools

- [oclif](https://github.com/oclif/oclif) is the most active project I can rely on to build Node.js-based CLI app.
- [Yargs](https://github.com/yargs/yargs) helps you build interactive command line tools, by parsing arguments and generating an elegant user interface.

## Code formatter

- [Prettier](prettier.io)

## Images

- [Holder](https://github.com/imsky/holder)
- PlaceIMG. https://placeimg.com/
- [Pexels](https://www.pexels.com/). Free stock photos.
- [Unsplash](https://unsplash.com). https://unsplash.com
- [Findshot](https://findshot.com/)

## Compressor

- Uglifyjs is kind of outdated. The new alternative is [Terser](https://www.npmjs.com/package/terser).

## Testing

- [Jest: JS Testing Framework](https://jestjs.io/)
- [Artillery](https://artillery.io). Load testing the servers
- [Cypress: Fast, easy and reliable testing for anything that runs in a browser](https://www.cypress.io/)
- [Mirage JS: API mocking library](https://miragejs.com/)
- [Polly.JS is a standalone, framework-agnostic JavaScript library that enables recording, replaying, and stubbing of HTTP interactions](https://netflix.github.io/pollyjs)
- [HTTP server mocking and expectations library for Node.js](https://github.com/nock/nock)

## Mocking Tools

- [Fake Online REST API for Testing and Prototyping](https://jsonplaceholder.typicode.com/)
- [Sinon.js](http://sinonjs.org/)
- [Chance](https://chancejs.com/). Generator of random strings, numbers, etc. to help reduce some monotony particularly while writing automated tests or anywhere else you need anything random

## Logging

- Logging library in Node.js [pino: super fast, all natural json logger](https://github.com/pinojs/pino)

## Useful Codepens

- [4 ways to unit test JS in Codepen
](https://codepen.io/brownerd/post/4-ways-to-unit-test-js-in-codepen)

## Scheduled Jobs

- [Agenda](https://github.com/agenda/agenda). Lightweight job scheduling for Node.js

# Utilities

- [Convert object keys to camel case using camelcase](https://www.npmjs.com/package/camelcase-keys). Note that if the key are an array than the items inside is an object than it will not be converted to `camelCase`
- [Highlight select fragments of a string using an HTML element and/or a class](https://www.npmjs.com/package/react-highlighter)
- [currency.js](https://currency.js.org)
- [uuid](https://www.npmjs.com/package/uuid)
- [language-mapping-list
](https://github.com/mozilla/language-mapping-list). List of all the known languages in their English and Native name with locales.
- [Transform SVGs into React components.](https://github.com/smooth-code/svgr)
- [Build forms in React, without tears](https://jaredpalmer.com/formik/)
- Retrying promise operation: [node-promise-retry](https://github.com/IndigoUnited/node-promise-retry), [async-retry](https://github.com/zeit/).
- [Nodemon](https://nodemon.io/). Utility that will monitor for any changes in your source and automatically restart your server. Perfect for development.
- [npkill](https://npkill.js.org/). Easily find and remove old and heavy node_modules folders
- [verge: Get viewport dimensions, detect elements in the viewport](https://github.com/ryanve/verge)
- [res: Device resolution detection module](https://github.com/ryanve/res)
- [faker.js - generate massive amounts of fake data in the browser and node.js](https://www.npmjs.com/package/faker)
- [Create, read and edit .zip files](https://github.com/Stuk/jszip)
- [Simple, programmatic `/etc/hosts` manipulation](https://github.com/feross/hostile)
- [Easily read/write JSON files in Node.js](https://www.npmjs.com/package/jsonfile)
- [form-data](https://www.npmjs.com/package/form-data)
- [minimist](https://github.com/substack/minimist). Parse argument options.
- [query-string: Parse query string from a URL](https://www.npmjs.com/package/query-string)
- [mime-types](https://www.npmjs.com/package/mime-types)

# Security

- [An authorization library that supports access control models like ACL, RBAC, ABAC in Node.js](https://github.com/casbin/node-casbin)
- Validation Libraries: [validate.js](https://github.com/ansman/validate.js), [joi](https://github.com/hapijs/joi)

# Hosting

- [Surge](https://surge.sh). Static web publishing for Front-End Developers.
- [Netlify](https://www.netlify.com/). Drop-dead simple deployment workflow. 
- Deploy MEAN stack using on AWS: [MEAN Certified by Bitnami](https://aws.amazon.com/marketplace/pp/B00NO1HJ56?qid=1588443370516&sr=0-2&ref_=srh_res_product_title)
- Node.js on AWS [Node.js Certified by Bitnami](https://aws.amazon.com/marketplace/pp/B00NNZUAKO?qid=1588443370516&sr=0-1&ref_=srh_res_product_title#pdp-usage)
- [Amazon Lightsail](https://aws.amazon.com/lightsail/)
- [Heroku](https://www.heroku.com/)
