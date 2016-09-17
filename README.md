## radd
`radd` is a CLI tool for scaffolding react/redux applications. 

It allows you to create new components, actions, and reducers, as well as update imports with a few simple commands

### Usage
```
radd startapp awesome
```
Creates 
```
awesome/
├── components
│   └── Main.js
└── redux
    ├── actions
    │   └── main.js
    ├── initialState.js
    ├── reducers
    │   └── main.js
    └── select.js
```
in the current working directory