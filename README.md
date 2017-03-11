# tstemplate

Mark's TypeScript template. A minimal skeleton project to get a TypeScript
project going. Tries to include as little as possible while still maintaining a
reasonably good dev experience.

# HOWTO

- Get a copy of the template:

```text
git clone https://github.com/overthink/tstemplate myproject
cd myproject
rm -rf .git
git init
```

- change the `CHANGEME` values in `package.json` to suit your project
- `npm install`
- `npm start`
- look at http://localhost:8000
- run `npm test` to test, or `npm run watch` to run tests on any file change

# Includes

- TypeScript 2.x
- webpack 2.x
- webpack-dev-server
- tape for testing
- static asset handling (copies into dist directory)

