## React Native Typescript

## Quickstart

To get started with our template, run one of the following commands:
```shell
# using npx and the github repo directly
npx react-native init MyApp --template=https://github.com/delyethan/react-native-template

```
```shell
# using npx with last react-native and the github repo directly
npx react-native@latest init MyApp --template=https://github.com/delyethan/react-native-template

```

Create swift Bridging by add new file swift to .xcworkspace file

fix Android 8.0 crash splash screen by config android/app/src/main/res/values-v26/styles.xml

```
<item name="android:windowIsTranslucent">false</item>
```

### dependencies

    {
    "@react-native-community/masked-view": "^0.1.9",
    "@react-native-firebase/app": "^6.4.0",
    "@react-native-firebase/auth": "^6.4.0",
    "@react-native-firebase/firestore": "^6.4.0",
    "@react-navigation/bottom-tabs": "^5.2.6",
    "@react-navigation/native": "^5.1.5",
    "@react-navigation/stack": "^5.2.10",
    "@types/lodash": "^4.14.149",
    "@types/react-native-vector-icons": "^6.4.5",
    "lodash": "^4.17.15",
    "mobx": "^5.15.4",
    "mobx-react": "^6.2.2",
    "moment": "^2.24.0",
    "react": "16.11.0",
    "react-hook-form": "^5.4.2",
    "react-native": "0.62.2",
    "react-native-fast-image": "^8.1.5",
    "react-native-gesture-handler": "^1.6.1",
    "react-native-global-props": "^1.1.5",
    "react-native-keyboard-aware-scroll-view": "^0.9.1",
    "react-native-linear-gradient": "^2.5.6",
    "react-native-material-ripple": "^0.9.1",
    "react-native-material-textfield": "^0.16.1",
    "react-native-reanimated": "^1.8.0",
    "react-native-safe-area-context": "^0.7.3",
    "react-native-screens": "^2.4.0",
    "react-native-splash-screen": "^3.2.0",
    "react-native-vector-icons": "^6.6.0",
    "rn-placeholder": "^3.0.0"
    }

### devDependencies

    {
    "@babel/core": "^7.6.2",
    "@babel/plugin-proposal-class-properties": "^7.8.3",
    "@babel/plugin-proposal-decorators": "^7.8.3",
    "@babel/plugin-transform-flow-strip-types": "^7.9.0",
    "@babel/runtime": "^7.6.2",
    "@react-native-community/eslint-config": "1.1.0",
    "@types/jest": "^24.0.24",
    "@types/react-native": "^0.62.0",
    "@types/react-test-renderer": "16.9.2",
    "@typescript-eslint/eslint-plugin": "^2.27.0",
    "@typescript-eslint/parser": "^2.27.0",
    "babel-jest": "^24.9.0",
    "eslint": "^6.5.1",
    "eslint-plugin-import": "^2.20.2",
    "eslint-plugin-react-hooks": "^4.0.4",
    "jest": "^24.9.0",
    "metro-react-native-babel-preset": "^0.58.0",
    "prettier": "^2.0.4",
    "react-test-renderer": "16.11.0",
    "typescript": "^3.8.3"
    }
