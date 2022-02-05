# MERN-jobify

㊫ MERN-04-Practice

#### Track your Job Search

Project in Action = [Jobify](https://www.google.com/)

#### Run The App Locally

- `npm run install-dependencies`
- rename `.env.temp` to `.env`
- setup values for - MONGO_URL, JWT_SECRET, JWT_LIFETIME
- `npm start`
- visit url http://localhost:3000/

#### Setup React App

- in MERN-jobify main directory `mkdir client`
- `cd client`, in client `npx create-react-app .`
- `npm start`, set editor/browser side by side
- copy/paste assets from complete project

#### Spring Cleaning

in src remove:

- App.css
- App.test.js
- logo.svg
- reportWebVitals.js
- setupTests.js

then fix App.js and index.js

#### Title and Favicon

- change title in public/index.html
- replace favicon.ico in public
- resources: (favicons)[https://favicon.io]

#### Normalise.css and Global Styles

- normalize.css: small css file that provides cross-browser consistency in the default styling of HTML elements.
- (normalize)[https://necolas.github.io/normalize.css/]
- `npm install normalize.css` and `import 'normalize.css'` in index.js (set before `import 'index.css' `)
- replace contents of index.css
- resources: Coding Addict (Default Starter)[https://youtu.be/UDdyGNlQK5W] ; Repo (Default Starter)[https://github.com/john-smilga/default-starter]

#### Landing Page

- react router and styled components right after
- in src: `mkdir pages` & `cd pages`, then `touch Landing.js`
- for now Landing.js
- create components
- setup basic return
