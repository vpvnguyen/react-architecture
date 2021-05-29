# react-architecture

## Domain Driven Design

```bash
# Infrastructure
├── store
│   ├── redux.js
│   ├── graphql.js
├── api
│   ├── TodoApi.js

# Application
├── App.js
├── config
│   ├── configureTheme.js
│   ├── Environment.js
├── routes
│   ├── Router.js
│   ├── TodoRoute.js
├── pages
│   ├── TodoPage.js

# Domain
├── domain
│   ├── Todo
│   │   ├── TodoIndex.js / index.js
│   │   ├── TodoContainer.js
│   │   ├── TodoItem.js
│   │   ├── TodoStyle.js / .css
│   │   ├── TodoContext.js
│   │   ├── TodoReducer.js
│   │   ├── useTodoHook.js
│   │   ├── TodoService.js
│   │   ├── TodoConstants.js

# UI
├── ui
│   ├── Theme.js
│   ├── Container.js
│   ├── Input.js
│   ├── Button.js

# Utilities
├── utils
│   ├── formatDate.js

# ...rest
├── node_modules
├── README.md
├── package.json
└── .gitignore
```
