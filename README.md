# material-recommendations-for-reactnative

## Library
This sections is all library i suggest for check how use tools or elements for development  and it have different resources.

- [React Native Elements](https://reactnativeelements.com/)
- [React Navigation](https://reactnavigation.org/)
- [React Native Async Storage](https://react-native-async-storage.github.io/async-storage/)
- [Reactotron](https://github.com/infinitered/reactotron)
- [React Native Testing Library](https://callstack.github.io/react-native-testing-library/docs/start/quick-start)
- [Jest](https://github.com/jestjs/jest)


## Suggested Repos

This sections is all repos i suggest for check how create structure project and it have different resources.

- [Bluesky App ](https://github.com/bluesky-social/social-app)
- [Ignite](https://github.com/infinitered/ignite/tree/master/boilerplate)
- [React native boilerplate](https://github.com/thecodingmachine/react-native-boilerplate)
- [Awesome React Native](https://github.com/jondot/awesome-react-native)
- [React Patterns](https://www.patterns.dev/react/)
- [Advanced React Pattern](https://github.com/epicweb-dev/advanced-react-patterns)
- [React native resource](https://github.com/vanGalilea/react-native-testing) 

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
