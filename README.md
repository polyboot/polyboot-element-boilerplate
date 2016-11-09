# polyboot-element-boilerplate

A starting point for to build Polyboot web components using Polymer.

## Installation
Assuming Node.js & Bower is already installed & running.

```
npm install
```

```
bower install
```

In case required for root user for Ubuntu or other linux distributor.
```
bower install --allow-root
```

## Serve your component locally
```
npm run start:dev
```

## Lint polyboot component
```
npm run lint
```

## Building Your Application

```
npm run build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

```
npm run start:bundled
```

```
npm run start:unbundled
```

## Running Tests

### Will run tests on all of your local browsers
```
npm run test:all
```

### Will only run tests in chrome
```
npm run test:chrome
```

### Will keep the browsers alive after test runs (refresh to re-run)
```
npm run test:alive
```
