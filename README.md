# Amazon-Style Shopping UI Demo

A React demo inspired by an online storefront. The dependency list includes React, React Router, Material-UI, Firebase, and Stripe client libraries.

## Requirements

- Node.js and npm
- Local Firebase configuration if required by the current app
- Stripe test-mode configuration only if the payment flow is enabled

## Run locally

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

## Build and tests

```bash
npm test
npm run build
```

These commands use the scripts provided by Create React App in this repository.

## Scope

This is a learning/demo clone, not an authorized Amazon product or a production commerce platform. Before exposing it publicly, verify authentication and database rules, protect all private credentials on the server, and use Stripe test mode until a payment integration has been reviewed. Do not put secret keys in React environment variables; browser-bundled values are visible to users.

## Maintenance

The project uses older React/Create React App and Material-UI dependencies. Check compatibility and security advisories before using it in a new production application.
