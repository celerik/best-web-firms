<div align="center" markdown="1">

<img src="https://www.bestwebfirms.com/img/badges/best-web-firms.png" alt="Bet Web Firms" width="112">

# Best Web Firms

![build](https://github.com/celerik/best-web-firms-react/workflows/build/badge.svg)
![deploy](https://github.com/celerik/best-web-firms-react/workflows/deploy/badge.svg)
![documentation](https://github.com/celerik/best-web-firms-react/workflows/documentation/badge.svg)
[![Coverage Status](https://coveralls.io/repos/github/celerik/best-web-firms-react/badge.svg?branch=master)](https://coveralls.io/github/celerik/best-web-firms-react?branch=master)

</div>

# What's it

This is a *Single Page Application* (SPA) built with [Create React App](https://github.com/facebook/create-react-app), [Redux](https://es.redux.js.org/) and [Material-UI](https://material-ui.com/).

The code is organized following an intuitive architecture and follows some of the best practices in *React* & *JavaScript* world, the following features are included in this code baseline:

- **Mock System**: All endpoints are mocked, so the app can run without being connected to a backend.
- **Internationalization**: All texts are localized, so the app support multiple languages.
- **Redux Architecture**: Organized in Action Creators, Reducers and Containers.
- **Component Oriented Architecture**: Organized in Containers, Pages, Navigation Controls and Common Controls.
- **Environments**: Support for multiple environments including Local, Dev, QA, Staging and Prod.
- **Security System**: Including Login, Password Recovery, User Management and Bearer Tokens.
- **Built-in controls**: Including Accordion, Autocomplete, Avatar, Checkfield, Datepicker, Multi Select, Modal Dialog, Select, Switch, Table, Textfield and Treeview.
- **Master Data System**: Including Main Menu, Footer, Profile Menu, Auto Spinner for ajax calls, Confirm Dialog and Toast Notifications.
- **Common Pages**: Including Settings, Home Page, Log Viewer, Master Data, Not Found Page, Roles and Users.
- **Ajax Interceptors**: To globally process requests and responses, send bearer tokens and handle errors.
- **Utilities**: Including Arrays, Dates, Language, Numbers, Objects, Strings and Validations.
- **Linters**: Including CSS and Javascript
- **Unit testing**: Including tests for Action Creators, Reducers and Utilities.
- **Styles**: Supporting SASS, JSS and CSS.

# Deployment artifacts
 - [Development Docker Image](https://github.com/celerik/best-web-firms-react/packages/159621): Published on merge to `master`.
 - [Production Docker Image](https://github.com/celerik/best-web-firms-react/packages/159627): Published on merge to `master` with commit msg containing keyword `[release]`.

# Environment Setup

### 1. Install Node.js
 - [Download](https://nodejs.org/es/download)

### 2. Install Git
- [Git Client](https://git-scm.com/downloads)
- [Source Tree](https://www.sourcetreeapp.com) (Optional)

### 3. Clone Repository
```shell
git clone https://github.com/celerik/best-web-firms-react.git
```

### 4. Install Visual Studio Code & Extensions
 - [Visual Studio Code](https://code.visualstudio.com/download)

Extensions:
 - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
 - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
 - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
 - [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
 - [Icons](https://marketplace.visualstudio.com/items?itemName=robertohuertasm.vscode-icons)
 - [NpmIntellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
 - [SortLines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)

# Run Project

 1. Install packages: `npm install`
 2. Build CSS files: `npm run build-css`
 3. Run JavaScript linter: `npm run lintj`
 4. Run CSS linter: `npm run lints`
 5. Run unit tests: `npm run test`
 6. Generate documentation: `npm run doc`
 7. Start project: `npm start`
 
 
# Documentation

 - Check out Component's documentation [here](https://github.com/celerik/best-web-firms-react/blob/gh-pages/README.md).
 
# What's next

Check out the road map of *best-web-firms-react* [here](ROADMAP.md).

# License

*best-web-firms* is licensed under the [MIT license](LICENSE).

# How to Contribute
Check out the contributing guide [here](CONTRIBUTING.md).
