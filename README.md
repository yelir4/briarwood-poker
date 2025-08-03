# briarwood poker
**Riley Guioguio, Matthew Stark**


## setup
ASSUMING YOU ARE ON WINDOWS (similar steps for Mac/Linux users)

This project uses Node.js version 22.11.0. We can use [Node Version manager](https://github.com/coreybutler/nvm-windows) to install 22.11.0 and manage different versions of node.js

- `nvm install 22.11.0`
- `nvm use 22.11.0`

Move to directory where you want to install the project, then
- `git clone https://github.com/yelir4/briarwood-poker.git`
- `cd o107_finalproject`
- `npm install`


## running application locally
Make sure terminal is in the project directory i.e. `xxxx\briarwood-poker\`, then

`node src/index.js` OR `npm start`

Then, visit in browser: http://localhost:3000

## pushing changes to main branch
Make sure to be in project directory, then
- `git add .`
- `git commit -m "<message>"`
- `git push origin main`

# pulling changes from main branch
Make sure to be in project directory, then
- `git pull origin main`

## what are the project files?
- package.json - project information and list of dependencies
- package-lock.json - specify version of project dependencies
- src/ - server side code
    - src/index.js - application entry point

## list of technologies used
- Node.js, Express, Sqlite3
- HTML, CSS, JavaScript