# Blue Lagoon

**A windowing system for web applications.**

## Tier 1 goals

This should become an old-school windowing GUI, suitable for creating online and offline applications and magazines.

Design goals:

- Rapid development of the project using easy-to-use UI components as Semantic UI and Bulma. Based on Vue.js.
- Good test coverage.
- Best practices throughout the development process.

The tech stack may change as we go: TypeScript, EcmaScript, SCSS, Vue, Vuex, Nightwatch, Mocha, Chai, Semantic UI, Bulma. Code is formatted with Prettier.

Question marks: Apollo.

Storage: local storage in the browser in Tier 1.

## Tier 2 goals

- Standalone executables via Electron.
- Maybe a separate (in standalone case bundled) back-end data storage solution. SQLite + Apollo sounds promising. Could be done via Express on Node.js, or Micronaut or Spring in Groovy or Java.

/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\/\\

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your unit tests
```
npm run test:unit
```

### Run your end-to-end tests
```
npm run test:e2e
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
