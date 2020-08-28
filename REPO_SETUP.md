# Repository Setup Steps

Below are the steps I took to set up this repository.

```bash
# Ensure nvm and npm was installed
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
nvm install v14.8.0
# Install eslint for linting Javascript code
# Following: https://medium.com/@RossWhitehouse/setting-up-eslint-in-react-c20015ef35f7
npm install eslint --save-dev
npm install eslint-plugin-react --save-dev
# Create node package info and linting config
npm init
eslint --init
# Test linter with local instance of eslint.js
./node_modules/eslint/bin/eslint.js src/*.js
```
