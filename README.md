# Clean React Template [CRT]

<div align="left">
<img src="https://img.shields.io/badge/version-1.0.0-blue">
<img src="https://badgen.net/github/stars/guerin-jerome/clean-react-template">
</div>

## Introduction

📖 This repository is based on bulletproof react repository of **alan2207** ([link of project](https://github.com/alan2207/bulletproof-react)), who inspired me a lot.

> "A simple, scalable, and powerful architecture for building production ready React applications."

This project relates about <ins>best practices</ins> and <ins>consistent tools</ins> to produce **efficient** application.

## To do

Replace all `TODO` in code by yours values except in `.gitattributes`.

🤝 **Feel free** :

- fork this project
- open pull request to improve this template
- create your own project based on this
- star this repo
- share with your network

### Scripts

List of scripts with **npm** :

```sh
$ npm install #to install dependencies
```

```sh
$ npm start #to start the project
```

> 💡 The project launched, is accesible on : http://localhost:3000.

```sh
$ npm test #to launch tests
```

```sh
$ npm run build #create package build to production
```

```sh
$ npm run eject #to remove build package of project, be careful !
```

Script with **npx** :

```sh
$ npx prettier --write . #format code with prettier
```

Script with **git** and **husky** :

```sh
$ git commit #when commit is started, husky will use prettier to format codes before
```

## Informations

👨‍💻 This template is configurated for VS Code editor, you can download on this link : https://code.visualstudio.com/download.

`.vscode` and `settings.json` allows you to format your code when you save each files.

### Configuration

| Name         | Version | Doc. link                           |
| ------------ | ------- | ----------------------------------- |
| ESLint       | 8.17.0  | https://eslint.org/                 |
| Prettier     | 2.7.0   | https://prettier.io/                |
| TypeScript   | 4.7.3   | https://www.typescriptlang.org/     |
| Husky        | 8.0.1   | https://typicode.github.io/husky/#/ |
| Redux        | 4.2.0   | https://redux.js.org/               |
| React-Router | 6.3.0   | https://reactrouter.com/            |
| Jest         | ^27.5.2 | https://jestjs.io/                  |

**Explanations :**

- **ESLint** - _ESLint is a static code analysis tool for identifying problematic patterns found in JavaScript code._
- **Prettier** - _Prettier is an opinionated code formatter, it improves code readability and makes the coding style consistent for teams._
- **TypeScript** - _TypeScript is a strict syntactical superset of JavaScript and adds optional static typing to the language._
- **Husky** - _Modern native Git hooks made easy._
- **Redux** - _Redux is an open-source JavaScript library for managing and centralizing application state._
- **React-Router** - _React Router keeps your UI in sync with the URL. It has a simple API with powerful features like lazy code loading, dynamic route matching, and location transition handling built right in._
- **Jest** - _Jest is a JavaScript testing framework._

### Architecture

🏛️ (cf. [link of inspired project](https://github.com/alan2207/bulletproof-react/blob/master/docs/project-structure.md))

```sh
src
|
+-- assets            # assets folder can contain all the static files such as images, fonts, etc.
|
+-- components        # shared components used across the entire application
|
+-- config            # all the global configuration, env variables etc. get exported from here and used in the app
|
+-- features          # feature based modules
|
+-- hooks             # shared hooks used across the entire application
|
+-- lib               # re-exporting different libraries preconfigured for the application
|
+-- providers         # all of the application providers
|
+-- routes            # routes configuration
|
+-- stores            # global state stores
|
+-- test              # test utilities and mock server
|
+-- types             # base types used across the application
|
+-- utils             # shared utility functions
```
