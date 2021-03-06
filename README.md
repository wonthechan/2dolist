# 2dolist-app
A simple to-do list application created with **Vue.js**(JavaScript Framework) and **Express**(back-end).

## Demo
Try it live on http://chan-2dolist.herokuapp.com (hosted on Heroku)
![screenshot](./screenshot-2dolist.jpg)
*Both Node.js and NPM should be installed in advance prior to the following instructions.*
## Install all dependencies
```
npm install
```

## Serve on localhost:8080 with hot reload
```
npm run serve
```

## Compiles and build for production with minification
```
npm run build
```

## Serve on localhost:5000 using Express(Node.js)
```
node server.js
```

### Features
- Add and remove as many todos as you want.
- Edit each todo on separated window popup.
- Setting a duedate for each todo is optional.
- It shows notification for overdue todos every 5 seconds.
- Turn on and off overdue notification with toggle-style button.
- All todos are stored in localStorage, so they are not gone even if you close the app.

### Dependencies used in this app
- [express](https://www.npmjs.com/package/express)
- [uuid](https://www.npmjs.com/package/uuid)
- [vue-js-modal](https://www.npmjs.com/package/vue-js-modal)
- [vue-js-toggle-button](https://www.npmjs.com/package/vue-js-toggle-button)
- [vue-notification](https://www.npmjs.com/package/vue-notification)
- [vuejs-datepicker](https://www.npmjs.com/package/vuejs-datepicker)

### Environment
- Ubuntu 18.04
- Google Chrome 
- Heroku
