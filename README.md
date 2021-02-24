This is the companion repository for Vite.js's [issue XX]().

The app has been created through `npm init @vitejs/app`.

To reproduce the error:
- `$ npm i`
- `$ npm run dev`
- open `http://localhost:3000` in the browser

The page is blank and the

> App.jsx:5 Uncaught SyntaxError: The requested module '/node_modules/.vite/redux-saga.js?v=d5e5e8ad' does not provide an export named 'runSaga'

error is reported in the JavaScript console.
