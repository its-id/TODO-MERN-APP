# TODO App

A simple TODO App just made a bit "FullStack".

## Features
- User can login and signup to save his/her todos.
- User can create a Todo.
- User can see their Todos
- User can mark the Todo as done.

## Instructions to Run

### Frontend
1. `cd frontend`
2. `npm i`
3. `npm run dev`

### Backend
1. `cd backend`
2. `npm i`
3. `npm run dev`

## Some Issues you can encounter
If get the `punnycode` error when running the backend. Simply:
1. Go to `node_modules` of backend.
2. Look for the folder **tr46**.
3. Go to index.js and
 
// Replace this:
    const punycode = require('punycode');
    // With this:
    const punycode = require('punycode/');