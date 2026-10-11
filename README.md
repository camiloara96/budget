# Family Budget

A small budgeting app for planning each paycheck, tracking recurring bills, and one-time expenses.
It runs in the browser and can be added to an iPhone home screen, where it opens full screen.

- `index.html` is the whole app.
- `firebase-config.js` points the app at its Firebase project (sign-in and data storage).
- `sw.js` lets the app open without a connection.

The budget data is not in this repository. It is stored in Firebase and only signed-in accounts can read it.
