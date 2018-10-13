# Electron Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Electron Changes

### File Additions and updates

* Procfile - This is used with foreman to make sure the React dev server is started before starting Electron
* src/electron-wait-react.js - This is also used to make sure the dev server is started before Electron
* Package.json - Updated and added several scripts (npm start is still used for development), added main, home, and build as well
* public/electron.js - This was /main.js copied from Electron's [electron-quick-start](https://github.com/electron/electron-quick-start) repository
* *Optional* .env - Adding `BROWSER="none"` will prevent the browser from opening when the dev server starts

### Scripts
* `npm start` will now open an electron window (as well as a browser unless using the above optional .env)

## Resources

* [Medium Article](https://medium.freecodecamp.org/building-an-electron-application-with-create-react-app-97945861647c)
* [Gist](https://gist.github.com/matthewjberger/6f42452cb1a2253667942d333ff53404)
* [Repository](https://github.com/simonsankar/Vnime)