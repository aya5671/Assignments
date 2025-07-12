-----Steps done in this folder:-----

1. FS Module (Sync & Async)
Create a file named `info.txt` containing basic information about yourself (name, age, university).
Then:
    -Read the file using `fs.readFileSync` and log the content to the console.
    -Read the same file using `fs.readFile` (asynchronous).
    -Create a new file `summary.txt` with a sentence like:
 `This file was read successfully and contains X characters.`

2. HTTP Module + Routing
Use the built-in `http` module to create a simple server with 3 routes:
- `/` -> Return a welcome HTML message.
- `/about` -> Return a short HTML paragraph about yourself.
- `/data` -> Read and return data from a `data.json` file as JSON.
  
3. Callback Hell to Promises
Create 3 files: `step1.txt`, `step2.txt`, `step3.txt`, each with a simple message.
Then:
   -Read them in sequence using nested callbacks (callback hell).
   -Refactor the same logic using promise chaining.
   -Do the same using async/await.
  
4. Custom Module
Create a file `math.js` that exports 4 functions: `add`, `sub`, `mult`, and `div`.
Then in another file `app.js`, import and use these functions to log results.

5. Basic Express App
Build a simple Express app with the following routes:
- GET `/` -> Return "Hello from Express!"
- GET `/users` -> Return user data from a `users.json` file.
- POST `/users` -> Accept new user data and append it to the file
