- Clone this repo
- to install dependencies: `npm install` or `yarn install`
- rename the file `example.firebaseConfig.js` to `firebaseConfig.js`
- and make sure to add your own Firebase config in this file as shown below.

## File Strucutre

```shell
├── assets ➡️ All static assets
├── components ➡️ All re-suable UI components for form screens
├── config
│   └── firebase ➡️ Firebase related config
│       └── context.js ➡️ Firebase high order component consumed in screen components
│       └── firebaseConfig.js ➡️ Firebase API keys
│       └── firebase.js ➡️ Firebase authentication helper methods
├── navigation
│   └── AppNavigation.js ➡️ Protected routes such as Home screen
│   └── AuthNavigation.js ➡️ Routes such as Login screen, when the user is not authenticated
│   └── index.js ➡️ Switch between different stack navigators including "Initial" screen
├── screens
│   └── ForgotPassword.js ➡️ Forgot Password screen component
│   └── Home.js ➡️ Protected route/screen component
│   └── Initial.js ➡️ Load initial assets component, and checks if the user is already logged in
│   └── Login.js ➡️ Login screen component
│   └── Signup.js ➡️ Register screen component
├── App.js ➡️ Entry Point for Mobile apps
├── app.json ➡️ Expo config file
└── babel.config.js ➡️ Babel config (should be using `babel-preset-expo`)
```
