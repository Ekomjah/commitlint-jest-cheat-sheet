# Recommended file structure woth tests and hooks
```
src/
│
├── components/
│   ├── Button/
│   │   ├── Button.jsx
│   │   ├── Button.css
│   │   └── Button.test.jsx        # Unit test for this component
│   │
│   ├── Header/
│   │   ├── Header.jsx
│   │   ├── Header.css
│   │   └── Header.test.jsx
│   │
│   └── index.js                   # Optional barrel file
│
├── hooks/
│   ├── useFetch.js
│   ├── useFetch.test.js           # Test for hook
│   ├── useLocalStorage.js
│   └── useLocalStorage.test.js
│
├── pages/
│   ├── Home/
│   │   ├── Home.jsx
│   │   ├── Home.css
│   │   └── Home.test.jsx
│   │
│   └── About/
│       ├── About.jsx
│       ├── About.css
│       └── About.test.jsx
│
├── utils/
│   ├── formatDate.js
│   └── formatDate.test.js
│
├── App.jsx
├── main.jsx
│
└── __tests__/                     # Optional global test dir
    ├── setupTests.js              # Config for Vitest + RTL (e.g. custom render)
    ├── integration/
    │   └── App.integration.test.jsx
    └── mocks/
        ├── handlers.js            # For MSW (mock API handlers)
        └── server.js
```
