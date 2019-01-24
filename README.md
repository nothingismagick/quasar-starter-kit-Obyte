![logo](/docs/art/firstByte.png)


##### An opinionated starter kit for Obyte, with Quasar.

# WIP 
Status: scaffolding, not ready for use

## Introduction

Mere inspiration make not the app alone - as they with great ideas may not necessarily great developers be. Especially within the domain of applied cryptography and virtual currency, novice’s mistakes are more likely than beginner’s luck. FirstByte minimizes these risks by enabling those with moderate skill (or a willingness to learn) to produce shippable best-practice apps for all major computing platforms from one code base and in record time. Tailored to meet the needs of both Obyte enthusiasts and professional developers, the core of FirstByte is built on the Quasar Framework and obyte.js - and is distributed under the permissive MIT license.

### Deliverables
Inheritance is a powerful pattern, and this project will leverage it. FirstByte in and of itself is a lerna-based monorepo hosted at a public git repository where all of the development and CI pipelines are managed. When it is viable, it will be available as a WIP via NPM and YARN as well as from IPFS and DAT. 

### Basics
Quasar delivers a number of things “from the core” that are technically available in all starters.
- quasar-cli for best in class development
- All ES6 language features available
- ESLint in Standard style
- the innate ability to build SPA, PWA, SSR, Cordova and Electron apps

### The Pure Flavour
The Pure flavour will be a minimal setup that extends the basic Quasar core with:
- a collection of maintenance scripts for development, publication and distribution
- multiple test-runners, including Jest, Cypress and Webdriver-based E2E with sample tests
- ESLint extended with A11Y “lifting”
- Gitlab pipelines and dockerfiles
- GraphQL / Apollo / Prisma API and DB
- the obyte.js library
- integration with now.js for immediate project delivery
- automated documentation of APIs and functions
- robust system configuration and secret management using ENV variables
- developer configurable colors, icons, background images, graphs and animations
- i18n language translation engine rigged for use with content, not just interface

### Documentation
In addition to that which is provided by Obyte, Quasar, vue.js and obyte.js, the FirstByte pure starter will describe in detail every component, plugin and script. The factors that make each flavour distinct will be described in minutia. Partially generated from JSDoc comments, and partially handwritten by the authors, the approach to be maintained is a “living document”, most likely to be built with Storybook.js. Further, the entire documentation will be i18n based and translated using the Utopian.io / Davinci service.

## Development
This project uses yarn, a modern version of node (10 at the time of this writing) and lerna for monorepo management. It is linted with ESLint and designed for Quasar 1.0 in mind, although it may be possible to use with legacy Quasar. 


### Install instructions
The project uses yarn. Refer to its [documentation](https://yarnpkg.com/en/docs/install) to install it.

##### Install lerna
```shell
yarn global add lerna
```

##### Install dependencies of all the packages
This will bootstrap all the projects of the monorepo. If you only want to install a specific project, open the project folder and follow the instructions in the README.md.

```shell
lerna link
lerna bootstrap
```

## Team
- [Daniel Thompson-Yvetot](https://github.com/nothingismagick)
- [Razvan Stoenescu](https://github.com/rstoenescu)
- [Grégory Latinier](https://github.com/gregory-latinier)

## License
MIT - Copyright 2018 Daniel Thompson-Yvetot and Razvan Stoenescu

FirstByte Logo & Wordmark - CC-ND-NC Daniel Thompson-Yvetot
