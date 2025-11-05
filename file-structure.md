# Recommended file structure woth tests and hooks
```
src/
│
├── index.css                     # global resets / base styles  
├── main.jsx                      # app entry point  
├── App.jsx                       # root component  
│
├── assets/                       # images, fonts, icons, etc.  
│   ├── logo.svg  
│   └── …  
│
├── components/                   # reusable UI components  
│   ├── Button/
│   │   ├── Button.jsx
│   │   ├── Button.module.css
│   │   └── Button.test.jsx
│   │
│   ├── Card/
│   │   ├── Card.jsx
│   │   ├── Card.module.css
│   │   └── Card.test.jsx
│   │
│   └── …  
│
├── hooks/                        # custom reusable logic  
│   ├── useFetch.js
│   ├── useFetch.test.js
│   ├── useLocalStorage.js
│   └── useLocalStorage.test.js
│
├── pages/                        # app “screens” or “views”  
│   ├── Home/
│   │   ├── Home.jsx
│   │   ├── Home.module.css
│   │   └── Home.test.jsx
│   │
│   ├── About/
│   │   ├── About.jsx
│   │   ├── About.module.css
│   │   └── About.test.jsx
│   │
│   └── Contact/
│       ├── Contact.jsx
│       ├── Contact.module.css
│       └── Contact.test.jsx
│
├── utils/                        # helper / utility functions  
│   ├── formatDate.js
│   └── formatDate.test.js
│
└── __tests__/                    # global + integration testing setup
       |
       |── setupTests.js             # Vitest + RTL config  
```
