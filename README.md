# storybook-addon-comments
### based on firebase database

[![npm](https://img.shields.io/npm/v/storybook-addon-comments.svg)](https://www.npmjs.com/package/storybook-addon-comments)
[![Greenkeeper badge](https://badges.greenkeeper.io/stk-dmitry/storybook-addon-comments.svg)](https://greenkeeper.io/)
[![Travis badge](https://api.travis-ci.com/stk-dmitry/storybook-addon-comments.svg?branch=master)](https://travis-ci.com/stk-dmitry/storybook-addon-comments)


## Install
```sh
yarn add storybook-addon-comments -D
```

```js
// .storybook/addons.js

import 'storybook-addon-comments';
```

```js
// .storybook/config.js

import setCommentsConfig from 'storybook-addon-comments';

setCommentsConfig({
  apiKey: "******",
  authDomain: "[name].firebaseapp.com",
  databaseURL: "https://[name].firebaseio.com",
  projectId: "[name]",
  storageBucket: "[name].appspot.com",
  messagingSenderId: "111111111111"
});
```
