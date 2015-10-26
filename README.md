## Why this fork?
We needed to have the StatusBarIOS to be shown.

## react-native-drawer-layout

A platform-agnostic drawer layout. Pure JavaScript implementation on iOS and native implementation on Android. Why? Because the drawer layout is a useful component regardless of the platform! And if you can use it without changing any code, that's perfect.

To use this component, you will need to enable the following Babel options:

- es7.decorators
- es7.classProperties
- es6.modules
- es6.constants
- es6.blockScoping

## Add it to your project

1. Run `npm install react-native-drawer-layout --save`
2. `var DrawerLayout = require('react-native-drawer-layout');`
3. Follow the [DrawerLayoutAndroid](https://facebook.github.io/react-native/docs/drawerlayoutandroid.html#content) docs -- the API is the same.

## Demo

![](https://raw.githubusercontent.com/iodine/react-native-drawer-layout/master/example.gif)
