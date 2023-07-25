# INSTALL NODEMON
```
npm install nodemon --save-dev
```

# INSTALL HAPI FRAMEWORK
```
npm i @hapi/hapi
```

# INSTALL ESLINT
```
npm install eslint --save-dev
```

# CONFIG ESLINT
```
npx eslint --init
```

```
How would you like to use ESLint? -> To check, find problems, and enforce code style.
What type of modules does your project use? -> CommonJS (require/exports).
Which framework did you use? -> None of these. 
Does your project use TypeScript? -> N.
Where does your code run? -> Node (pilih menggunakan spasi).
How would you like to define a style for your project? -> Use a popular style guide.
Which style guide do you want to follow? -> (Anda bebas memilih, sebagai contoh pilih AirBnB).
What format do you want your config file to be in? -> JSON.
Would you like to …… (seluruh pertanyaan selanjutnya) -> Y.
```

# ADD THIS TO PACKAGE
```
"scripts": {
    "test": "jest",
    "start": "nodemon index.js",
    "lint" : "eslint ./"
},
```

# STRUCTURE
```
notes-app-back-end
├── node_modules
├── src
│ ├── handler.js
│ ├── notes.js
│ ├── routes.js
│ └── server.js
├── .eslintrc.json
├── package-lock.json
└── package.json
```

# CLIENT APP
[Client App](http://notesapp-v1.dicodingacademy.com/)

# ADD THIS TO .eslintrc.json
```
{
    "rules": {
        "no-console": "off"
    }
}
```