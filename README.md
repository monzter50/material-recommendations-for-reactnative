# material-recommendations-for-reactnative

## Library
- [React Native Elements](https://reactnativeelements.com/)
- [React Navigation](https://reactnavigation.org/)
- [React Native Async Storage](https://react-native-async-storage.github.io/async-storage/)

## Suggested Repos

- [Bluesky App ](https://github.com/bluesky-social/social-app)
- [Ignite](https://github.com/infinitered/ignite/tree/master/boilerplate)
- [React native boilerplate](https://github.com/thecodingmachine/react-native-boilerplate)
- [Awesome React Native](https://github.com/jondot/awesome-react-native)
## Suggested Architecture Folders

A common architecture for React Native projects includes:

- **src**: Main folder for source code.
- **components**: Reusable components.
- **screens**: Application pages.
- **navigation**: Navigation settings.
- **store**: Redux configuration, including slices, stores, and reducers.
- **assets**: Static files such as images and fonts.
- **utils**: Auxiliary utilities and functions.
- **services**: API services and backend calls.
- **config**: Global configuration of the application.

```
my-react-native-app/
├── android/
├── ios/
├── assets/
│   ├── fonts/
│   └── images/
├── src/
│   ├── components/
│   │   ├── Button/
│   │   │   ├── Button.js
│   │   │   └── Button.styles.js
│   │   └── Header/
│   │       ├── Header.js
│   │       └── Header.styles.js
│   ├── screens/
│   │   ├── Home/
│   │   │   ├── Home.js
│   │   │   └── Home.styles.js
│   │   └── Profile/
│   │       ├── Profile.js
│   │       └── Profile.styles.js
│   ├── navigation/
│   │   └── AppNavigator.js
│   ├── store/
│   │   ├── slices/
│   │   │   ├── userSlice.js
│   │   │   └── productSlice.js
│   │   ├── store.js
│   │   └── rootReducer.js
│   ├── services/
│   │   └── apiService.js
│   ├── utils/
│   │   ├── constants.js
│   │   └── helpers.js
│   └── config/
│       └── env.js
├── App.js
├── package.json
└── README.md
```
