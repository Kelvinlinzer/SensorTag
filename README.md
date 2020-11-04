Steps to run the project:

```
> npm i
> npx react-native link react-native-ble-plx
> cd android && ./gradlew build
```

It may complain the sdk is not found in the third step. If so, create local.properties, and add sdk path.

```
sdk.dir=/Users/kelvinli/Library/Android/sdk
```

Then copy the released version(android/app/build/outputs/apk/release) to phone, and install.
