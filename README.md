# My Tool Box
A long list of tools, frameworks, libraries and applications which I found interesting!

## Table of Contents




## Accessibility

+ ### a11y project

  A website that has been created to help developer to create websites and apps that meets the accessibility standard. Contains a lot of useful resources.

  - [x] Free content

  [Poke](https://a11yproject.com) to check it out

+ ### Axe

  Accessibility engine for automated Web UI testing. It comes in the forms of browser extensions and npm package, so developers could use it both on their development machine and CI pipeline.

  - [x] Open source
  - [x] Free to use for both personal and business

  [Poke](https://github.com/dequelabs/axe-core) to check it out

  **[⬆ back to top](#table-of-contents)**


## Analytics

+ ### Google Analytics

  Collects data from websites or web apps for later analysis on its website or mobile app.

  - [x] Free to use for both personal and business

  [Poke](https://marketingplatform.google.com/about/analytics) to check it out

+ ### Snowplow - self hosted analytics

  Similar to Google Analytics in a lot of ways, but allows for more customisable and allows data to be saved in specified locations instead of Snowplow's servers.

  - [x] Open source
  - [x] Self hosted

  [Poke](https://snowplowanalytics.com) to check it out

  **[⬆ back to top](#table-of-contents)**


## Development Services

+ ### Netlify - all-in-one service for web apps

  Deploy modern static websites with CDN, Continuous deployment, 1-click HTTPS, and many more services. Simply connect Github or other git hosting provider, then with a few clicks Netlify will deploy and host it for you. One of the features that impressed me the most is how it builds every commit that is pushed, this means you have a history of everything that you could go to one of their generated URLs and look at what the web app looked like many commits ago.

  Simple to use and my go to service.

  - [x] Free tier available

  [Poke](https://www.netlify.com) to check it out

+ ### ZEIT - serverless cloud platform

  ZEIT Now is a cloud platform for serverless deployment. It enables developers to host websites and web services that deploy instantly, scale automatically, and require no supervision, all with minimal configuration.

  - [x] Free tier available

  [Poke](https://zeit.co) to check it out

  **[⬆ back to top](#table-of-contents)**


## CMS

### Contentful - headless CMS

One of the most flexible and powerful headless CMS I've used to date. Allows easy integration with different languages and frameworks. It even supports graphQL querying instead of REST APIs.

- [x] Free tier available

[Poke](https://www.contentful.com) to check it out

### Sanity IO - headless CMS

Another headless CMS that seems to offer very similar features compared to Contentful.

- [x] Open source
- [x] Free tier available

[Poke](https://www.sanity.io) to check it out

### Prismic - headless CMS

Again another headless CMS.

- [x] Free tier available

[Poke](https://prismic.io) to check it out



## JavaScript Frameworks

*Section WIP*

* Vue
* React
* Angular
* https://riot.js.org
* https://cycle.js.org
* https://mithril.js.org
* Preact
* Polymer
* Marko
* Inferno
* Reactive
* UIKit
* slim.js
* Ember
* Aurelia
* Rax
* Cyclow
* https://github.com/NervJS/nerv
* Gem.js
* Webix UI
* KnockbackJS
* Backbone.js
* Shiva



## JavaScript Static Typing Tools

*Section WIP*

* Typescript
* Flow
* JSdoc



## JavaScript Libraries

### VX

**VX = react + d3**

> vx is a collection of reusable low-level visualization components. vx combines the power of d3 to generate your visualization with the benefits of react for updating the DOM.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/hshoff/vx) to check it out



## Languages

### JavaScript

Only the most popular programming language.

[Poke](https://developer.mozilla.org/bm/docs/Web/JavaScript) to check it out

*Section WIP*

* Elm
* Rust
* Elixir
* Golang
* Kotlin
* HCL - HashiCorp configuration language



## Mobile

### Flutter

> Flutter is Google’s mobile app SDK for crafting high-quality native interfaces on iOS and Android in record time. Flutter works with existing code, is used by developers and organizations around the world, and is free and open source.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://flutter.io) to check it out

### React Native

> React Native lets you build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI from declarative components. 

The biggest benefit of React Native is how similar it is to React. It will generate native apps based on the React code written (hence the name), this means native app level of performance. However, there still seems to be a lot of challenge with this when it comes to building apps both for iOS and Android (Airbnb moved away from it to native back in Jun 2018).

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://facebook.github.io/react-native) to check it out

### Cordova

> Cordova wraps your HTML/JavaScript app into a native container which can access the device functions of several platforms. These functions are exposed via a unified JavaScript API, allowing you to easily write one set of code to target nearly every phone or tablet on the market today and publish to their app stores.

Mobile apps using Cordova tends to have worse performance than native apps. However, with Cordova means it is possible to write code once then deploy to all sorts of devices (as long as they are supported by Cordova).

- [x] Open Source
- [x] Free tool

[Poke](https://cordova.apache.org) to check it out

### Bazel

**Building and testing Android apps**

> Bazel is a tool that automates software builds and tests. Supported build tasks include running compilers and linkers to produce executable programs and libraries, and assembling deployable packages for Android, iOS and other target environments.

- [x] Open Source
- [x] Free tool

[Poke](https://bazel.build) to check it out



## Testing

Some keywords:

* E2E - End-to-End testing, this is carrying out user behaviour tests on the browser. Often running core user journies hitting both real front-end and back-end of the web application, hence the name.

### Ava

**Unit testing library**

A JavaScript test library that focuses on simplicity and lightweight design. To the point that it doesn't even have mocking built-in and it is recommended to use something like sinon.js for that. Running test concurrently is another one of its main selling points.

Update (17th April 2019): after migrating we Jest, we found 10x performance improvement. There is very little reason to pick Ava over Jest at this stage.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/avajs/ava) to check it out

### Jest

**Unit testing framework**

Open sourced by Facebook, a complete testing framework that is well crafted and packaged together. With this people very rarely would need to install any other unit-testing related packages. The framework also detects how many threads the current machine/server has and runs tests in a way that is most effecient (e.g. concurrently on multi-threaded CPUs, consecutively on single threaded CPUs).

Compared to Ava, there is no need to install sinon.js since this framework has mocking built-in and in a lot of ways is easier to use.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://jestjs.io) to check it out

### Karma

**E2E testing framework**

> Karma is essentially a tool which spawns a web server that executes source code against test code for each of the browsers connected. The results of each test against each browser are examined and displayed via the command line to the developer such that they can see which browsers and tests passed or failed.

Karm is used for End-to-End (E2E) tests. It has been around for a while, so I'd personally pick something else over this. E.g. Cypress (below) essentially replaces Karma because it does all of this already and much more.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://karma-runner.github.io) to check it out

### Mocha

**Unit & E2E testing framework**

> Mocha is a feature-rich JavaScript test framework running on Node.js and in the browser, making asynchronous testing simple and fun. Mocha tests run serially, allowing for flexible and accurate reporting, while mapping uncaught exceptions to the correct test cases.

I have only used Mocha for Unit testing, but it seems like it could support E2E tests as well.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://karma-runner.github.io) to check it out

### Jasmine

**Unit testing framework**

> Jasmine claims to be a behavior-driven development framework, but it is just a unit testing tool for testing JavaScript code. It does not depend on any other JavaScript frameworks. It does not require a DOM. And it has a clean, obvious syntax so that you can easily write tests.

I personal would never use Jasmnine when I could use Jest. Imo Jest is better in almost everyway: easy to set up, batteries included, powerful APIs, and etc.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://jasmine.github.io) to check it out

### Chai

**Unit & E2E test assertion library**

> Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.

Similar to Sinon below, Chai is meant to work with other libraries and frameworks. There is very little reason to pick this tool up, unless the (testing) tech stack is custom made and requires a good assertion library. E.g. Chai could be used with Webdriver.io.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://www.chaijs.com) to check it out

### Sinon

**Test spies, stubs and mocks**

Standalone test spies, stubs and mocks for JavaScript. This is used in conjunction with any unit testing framework e.g. Ava.

Another reason for using Jest ist that it has mocking, stubbing and spying included out of the box.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://sinonjs.org) to check it out

### Cucumber and Gherkin

**Behaviour Driven Development (BDD) Testing**

Cucumber and Gherkin is a very popular tool among Java BDD testing. In JavaScript, this is mostly used in End to End (E2E) tests unlike Jasmine which is just another Unit testing tool.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/cucumber/cucumber-js) to check it out

### Cypress

**E2E testing framework and tool**

> The Cypress Test Runner is a hybrid application/framework/service all rolled into one. It takes a little bit of other testing tools, brings them together and improves on them.

It allows writting testing by clicking and browsing the site, instead of hand write the code like most of the other solutions out there. Other features are not as crazy, but the previous point alone is enough to attract a lot of customers.

- [x] Open source
- [x] Test Runner is free to use for both personal and business
- [x] Web Service (optional) has free tier available

[Poke](https://www.cypress.io) to check it out

### CodeceptJS

**E2E framework with different engines**

If you plan on implementing a custom E2E test stack, then look no further. CodeceptJS will allow all kinds of combinations of tools with ease, this means you can swap out test engines as you wish or ultilise them all (Selenium-based WebDriver,  Protractor, Chrome-based Puppeteer or Electron-based Nightmare). 

CodeceptJS uses its own syntax for writing the E2E scenarios. However, the syntax is very close to spoken English.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://codecept.io) to check it out

### Webdriverio

**WebDriver test framework**

Webdriverio was a big step up compared to how Selenium testing were done a few years back. But this is again, lagging behind compared to the newer tools that came out more recently. Due to the power of Selenium and the fact this is building on top of it, it will probably be around in the future, but with tools such as Cypress and CodeceptJS I can see Webdriverio being used all that much going forward.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://webdriver.io) to check it out

### Selenium WebDriver

**Cross browser testing**

Selenium will allow multi-browser testing compared to other tools which often is either based on no browser (e.g. PhantomJS or NightmareJS) or based on a single browser (e.g. Puppeteer). With the addition of Selenium WebDriver, it will now support headless browser testing.

Since there are not many other good solutions for cross browser testing, this is the only reason why it is still around.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://www.seleniumhq.org) to check it out

### PhantomJS

**Headless Browser**

PhantomJS is a headless web browser scriptable with JavaScript.

From the state of its website, you can tell it is no longer a popular tool.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](http://phantomjs.org) to check it out

### Protractor

**E2E Engine**

> Protractor is an end-to-end test framework for Angular and AngularJS applications. Protractor runs tests against your application running in a real browser, interacting with it as a user would.

I used this back in the AngularJS (1.x) days, it has been a long time and not sure how the landscape has shifted in the past few years.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://www.protractortest.org) to check it out

### Puppeteer

**E2E Engine**

> Puppeteer is a Node library which provides a high-level API to control Chrome or Chromium over the DevTools Protocol. Puppeteer runs headless by default, but can be configured to run full (non-headless) Chrome or Chromium.

With Edge moving to Chromium, this will surely become a popular tool and a major player in the days to come.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/GoogleChrome/puppeteer) to check it out

### NightmareJS

**E2E Engine**

> Nightmare is a high-level browser automation library from Segment. Under the covers it uses Electron, which is similar to PhantomJS but roughly twice as fast and more modern.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/segmentio/nightmare) to check it out

### Pact

**Consumer Driven Contract Testing**

A similar to BDD approach to integration testing between backend services with either other backend services and frontend applications.

- [x] Open source
- [x] Free to use for both personal and business
- [x] Self hosted

[Poke](https://docs.pact.io) to check it out

### Stryker

**Multation Testing**

This tool effectively tests the quality of the unit tests in a given project. 100% coverage means less and less now we move to component based unit testing e.g. we can have a basic test that renders a component, which will end up with 90%+ coverage.

> Bugs, or mutants, are automatically inserted into your production code. Your tests are ran for each mutant. If your tests fail then the mutant is killed. If your tests passed, the mutant survived. The higher the percentage of mutants killed, the more effective your tests are.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://stryker-mutator.io) to check it out

### Allure Framework

**Test Reporter**

A flexible lightweight multi-language test report tool. The framework current supports `Jasmine`, `Cucumber.JS` and `Mocha`.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/allure-framework/allure-js) to check it out



## GitHub Projects

### Serverless

**Framework for serverless apps**

A framework for building applications comprised of microservices that uses new event-driven compute services, like AWS Lambda, Google Cloud Functions, and etc.

- [x] Open source

[Poke](https://github.com/serverless/serverless) to check it out



## Tools & Services

### Apiary - Creating dummy APIs

This is a fantastic tool for quickly throwing together a dummy API for Frontend guys to start their work, whilst the Backend gets built. Define everything using `API Blueprint` and `OpenAPI (Swagger)` then have documentation generated as well!

- [x] Free tier available

[Poke](https://apiary.io) to check it out

### Cloudnary - image storage and optimization

A service that hosts media assets such as image and videos then serve them out in different formats, quality via unique URLs.

- [x] Free tier available

[Poke](https://cloudinary.com) to check it out

### Debuggex - regular expression performance visualiser

An awesome tool that will show you visually how the Regex will perform. This is extremely useful, and you won't deploy any poor performing Regex again!

- [x] Free tool
- [x] Free tier available

[Poke](https://www.debuggex.com/) to check it out

### Regex101 - regular expression writer

A simple to use web app for writing Regex in a few different languages, nice visual design and user/developer friendly.

- [x] Free tool

[Poke](https://regex101.com) to check it out

### semver - semantic version calculator

Still struggling with semantic versions and what symbols such as `~` and `^` does? This tool will let you try them all out, so you can be 100% sure before settling on a package version. 

- [x] Free tool

[Poke](https://semver.npmjs.com) to check it out

### Squoosh

An image compression web application provided by Google Labs.

- [x] Open source
- [x] Free tool

[Poke](https://squoosh.app) to check it out



## Miscellaneous

### Developer Roadmap

> A fairly detailed and useful amount of information presentated in an easy to consume way. It should provide a good overview for developers new or old about the key technology on the market. This is mostly web focused, so everything is broken down into Frontend, Backend and DevOps.

- [x] Free content

[Poke](https://github.com/kamranahmedse/developer-roadmap) to check it out

### Developer Roadmap for React

> Similar to `Developer Roadmap` above, this is more focused dive into React side of things. It has listed all the key packages and technology developers often work with when they use REACT.

- [x] Free content

[Poke](https://github.com/adam-golab/react-developer-roadmap) to check it out

### enlight.nyc

A platform created by a single individual, where it hosts a number of small projects which allows hands-on experience.

It is a cool idea, however, I think Glitch in this section is a more mature platform.

- [x] Free content

[Poke](https://enlight.nyc) to check it out

### Freecodecamp - learn about web development

A non-profit site that has a lot of web development courses and resources.

- [x] Free content

[Poke](https://www.freecodecamp.org) to check it out

### Glitch - discover project ideas

A site where people post their projects for the rest of the world to see. This site allows allow anyone to fork any project with a click and start playing around with that project.

> From useful tools that solve problems at work, to cutting-edge VR experiences, smart bots, and apps that help advance important causes, Glitch is a unique community where people have built over a million projects for you to discover, with new ones are popping up every day.

- [x] Free content

[Poke](https://glitch.com) to check it out

### Raw Therapee - Raw image enhancing tool

A free alternative tool to Adobe's lightroom, worth trying out.

- [x] Free tool

[Poke](https://rawtherapee.com) to check it out

### Resolver - complaint helper

Helps consumers to complain when things don't go our way, so you don't need to do all the emailing and be stressed about it.

- [x] Free service

[Poke](https://www.resolver.co.uk) to check it out
