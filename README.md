# Shop Shop

E-commerce platform that handles complex state management using Redux. Centralized all of the application's data in state globally to make it easier to share state across the entire application. Added shopping cart, offline functionality, and process secure payments with Stripe service. 

## Table of Contents

* [Setup](#setup)
* [Usage](#usage)
* [Deployment](#deployment)
* [Contributing](#contributing)
* [License](#license)

## Setup
:floppy_disk:

Uses the following tools in this repository:

- [React](https://reactjs.org/)
  - Open-source, declarative, component-based JavaScript library for building user interfaces. It’s maintained by Facebook, and it can be used to develop of single-page applications (SPA).
- [GraphQL](https://graphql.org/)
  - GraphQL is a query language for APIs and a runtime for fulfilling those queries with your existing data.
- [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
  - Open-source, spec-compliant GraphQL server that's compatible with any GraphQL client, including Apollo Client. Uses apollo-server-express package to integrate GraphQL into Express.js server, and the @apollo/client package to make requests from React front end to the GraphQL API.
- [Apollo Client](https://www.apollographql.com/docs/react/)
  - All-in-one dependency that enables connection to a GraphQL API server and execute queries or mutations using their own special form of React Hooks.
- [React Router](https://graphql.org/)
  - Collection of navigational components that compose declaratively with the application, allowing single-page React applications behave more like multi-page applications.
- [concurrently](https://graphql.org/)
  - Runs multiple processes, or servers, from a single command-line interface, rather than opening multiple terminals to start multiple servers. Tracks multiple outputs in one place and will stop all processes if one fails.
- [Stripe](https://stripe.com/)
  - Suite of online payment processing APIs that powers commerce for online businesses of all sizes, allowing them to accept and process payments online.
- [Stripe.js](https://stripe.com/docs/payments/elements)
  - Stripe's JavaScript library for building payment flows. Uses Stripe Elements, a set of prebuilt, customizable UI components to allow platforms to collect sensitive payment information. Also provides a single interface for Apple Pay, Google Pay, and the Payment Request API.

Repository splits into `client` and `server` sections to handle different parts of the development mode.

## Usage
:keyboard:

If the repository was cloned, run the files with `npm install` and start the server with `npm run develop`.

## Deployment
:computer:

No deployed app.

## Contributing
:octocat:

[paperpatch](https://github.com/paperpatch)

## License
:receipt: