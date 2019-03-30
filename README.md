# Project Sparkles
## Setup
- npm install
- cd into functions/ and run: npm install

## Build Instructions
- npm run build:firebase
- Deploy: firebase deploy --only functions,hosting
- Hosting: https://project-sparkles-75130.firebaseapp.com

## Troubleshooting
- Firebase deploy set up instructions: https://gist.github.com/Dabolus/314bd939959ebe68f57f1dcebe120a7e
- if deployment complains about firebase-admin, run  this within functions/ folder: npm install --save-exact firebase-functions@0.7.0 npm install --save-exact firebase-admin@5.4.0