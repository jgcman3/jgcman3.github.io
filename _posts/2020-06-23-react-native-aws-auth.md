---
title: "User Authentication with React Native & AWS"
date: 2020-06-23 18:02:28 -0400
categories: react-native aws auth amplify
---

## Create a new React Native app

To get started, initialize a new React Native project.

```bash
npm install -g expo-cli
```
```bash
expo init -g authApp
```

## Install Amplify libraries

Next, install the local Amplify dependencies in this project folder.

```bash
npm install aws-amplify aws-amplify-react-native @react-native-community/netinfo
```

Next, open <b>App.js</b> and add the following lines of code at the top of the file below the last import : 

```typescript
import Amplify from 'aws-amplify'
import config form './aws-config'
```