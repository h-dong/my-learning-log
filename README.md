# My Learning Log
A long list of tools, frameworks, libraries and applications which I found interesting!



## Accessibility

### a11y project - accessibility resources

A website that has been created to help developer to create websites and apps that meets the accessibility standard. Contains a lot of useful resources.

- [x] Free content

[Poke](https://a11yproject.com) to check it out

### Axe - accessibility testing

Accessibility engine for automated Web UI testing. It comes in the forms of browser extensions and npm package, so developers could use it both on their development machine and CI pipeline.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/dequelabs/axe-core) to check it out


## Analytics

### Google Analytics

Collects data from websites or web apps for later analysis on its website or mobile app.

- [x] Free to use for both personal and business

[Poke](https://marketingplatform.google.com/about/analytics) to check it out

### Snowplow - self-hosted analytics

Similar to Google Analytics in a lot of ways, but allows for more customisable and allows data to be saved in specified locations instead of Snowplow's servers.

- [x] Open source
- [x] Self hosted

[Poke](https://snowplowanalytics.com) to check it out



## CI/CD, Cloud services

### Netlify - all-in-one service for web apps

Deploy modern static websites with CDN, Continuous deployment, 1-click HTTPS, and many more services. Simply connect Github or other git hosting provider, then with a few clicks Netlify will deploy and host it for you. One of the features that impressed me the most is how it builds every commit that is pushed, this means you have a history of everything that you could go to one of their generated URLs and look at what the web app looked like many commits ago.

Simple to use and my go to service.

- [x] Free tier available

[Poke](https://www.netlify.com) to check it out

### ZEIT - serverless cloud platform

ZEIT Now is a cloud platform for serverless deployment. It enables developers to host websites and web services that deploy instantly, scale automatically, and require no supervision, all with minimal configuration.

- [x] Free tier available

[Poke](https://zeit.co) to check it out



## CMS

### Contentful - headless CMS

One of the most flexible and powerful headless CMS I've used to date. Allows easy integration with different languages and frameworks. It even supports graphQL querying instead of REST APIs.

- [x] Free tier available

[Poke](https://www.contentful.com) to check it out

### Sanity.io - headless CMS

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



## JavaScript static typing

*Section WIP*

* Typescript
* Flow
* JSdoc



## JavaScript Libraries

### VX - react + d3

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

### Bazel - Building and testing Android apps

> Bazel is a tool that automates software builds and tests. Supported build tasks include running compilers and linkers to produce executable programs and libraries, and assembling deployable packages for Android, iOS and other target environments.

- [x] Open Source
- [x] Free tool

[Poke](https://bazel.build) to check it out



## Testing

### Ava - JS unit testing library

A JavaScript test library that focuses on simplicity and lightweight design. To the point that it doesn't even have mocking built-in and it is recommended to use something like sinon.js for that. Running test concurrently is another one of its main selling points.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://github.com/avajs/ava) to check it out

### Jest - JS unit testing framework

Open sourced by Facebook, a complete testing framework that is well crafted and packaged together. With this people very rarely would need to install any other unit-testing related packages. The framework also detects how many threads the current machine/server has and runs tests in a way that is most effecient (e.g. concurrently on multi-threaded CPUs, consecutively on single threaded CPUs).

Compared to Ava, there is no need to install sinon.js since this framework has mocking built-in and in a lot of ways is easier to use.

- [x] Open source
- [x] Free to use for both personal and business

[Poke](https://jestjs.io) to check it out

### Pact - Consumer Driven Contract Testing

A similar to BDD approach to integration testing between backend services with either other backend services and frontend applications.

- [x] Open source
- [x] Free to use for both personal and business
- [x] Self hosted

[Poke](https://docs.pact.io) to check it out



## GitHub projects

### Serverless - framework for serverless apps

A framework for building applications comprised of microservices that uses new event-driven compute services, like AWS Lambda, Google Cloud Functions, and etc.

- [x] Open source

[Poke](https://github.com/serverless/serverless) to check it out



## Tools & services

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

[Poke](https://cloudinary.com) to check it out

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
