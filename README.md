# TODO App

A simple TODO App just made a bit "FullStack". 🔨

## Basic Features
- User can login and signup to save his/her todos.
- User can create a Todo.
- User can see their Todos
- User can mark the Todo as done.

## Add-On Work
- Email verification w/o OTP, JWT Authentication & Route Protection.
- Coded entirely in TS (FE & BE, including TYPE validation).
- Complete CRUD operations and DB storage.
- State Management using Context.
- Adheres industry standard coding practices.

## Future Works
- Giving User Todos based on selected date.
- Implementing OTP verification, Google and other third party auth.
- Maybe some UI revamps.

## Instructions to Run

### Frontend
1. `cd frontend`
2. `npm i`
3. `npm run dev`

### Backend
1.  `cd backend`
2. `npm i`
3. `npm run dev`

## Some Issues you can encounter
If get the **`punnycode`** error when running the backend. Simply:
1. Go to `node_modules` of backend.
2. Look for the folder **tr46**.
3. Go to index.js and
	```
	// Replace this:
	const punycode = require('punycode');
	// With this:
	const punycode = require('punycode/');
	```
	
Always open to any issues or collaborations. Let's go 🚀