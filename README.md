# Basic TS Template

### 1.- yarn install

### 2.- yarn run dev

```
"scripts": {
    "build": "tsc",
    "build:watch": "tsc --watch",
    "nodemon": "nodemon ./dist/index.js --watch ./dist/**/*",
    "dev": "npm-run-all build --parallel build:watch nodemon"
  }
```
