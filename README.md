# Generator-abstack-vuejs
A yeoman generator for Vue.js.

## Usage
You must install the [yeoman](https://github.com/yeoman/yeoman) first:

```bash
npm install -g yo
```

Then:

```bash
# install
npm install -g generator-abstack-vuejs

# generate project
yo abstack-vuejs
```

## include
- Development
  - npm script: `npm run dev`
  - webpack-dev-server
  - hot-module-replacement
  - lint code in pre-loader
  - source-map support

- Production
  - extract css into a single file
  - compress javascript
  - add CSS prefix automatic with autoprefixer
  - rename all static files with their content hash

- Test
  - unit test with [Karma](https://karma-runner.github.io), [Mocha](https://mochajs.org/), [Chai](http://chaijs.com/)
  - come soon...

## Changelog
Visit [release notes](https://github.com/PeachScript/generator-abstack-vuejs/releases)

Inspired by [vuejs-templates/webpack](https://github.com/vuejs-templates/webpack).
