# FOR STUDYING REACT NATIVE CLI

> 오늘의 야구 앱 개발 전 리네 cli 공부용 레포
> <br/>
> <br/>

# 개발환경 세팅

<br />

## ruby 2.7.0 으로 업데이트

<p>루비 업데이트 관리를 위한 rbenv 설치</p>
<strong>설치 명령어</strong>
<br/>

<code>brew install rbenv</code>
<br/>
<code>rbenv init</code>
<br/>
rbenv init을 했을 때 안내가 나오는대로 특정 파일(Ex. ~/.zshrc)에 코드를 추가.

### rbenv init 위해 코드 추가 방법

https://hee-dev.tistory.com/10
<br />
<br />

### ruby vesion update 방법

https://hee-dev.tistory.com/10

<br />
<br />
<br />

## cocoapods 설치

<strong>설치 명령어</strong>
<br/>

<code>gem install cocoapods</code>
<br/>

<br/>
<strong>설치 확인 위해 버전 확인</strong>
<br/>
<code>pod --version</code>

<br/>
<br/>

## Watchman 설치

- Watchman은 특정 폴더나 파일을 감시하다가 변화가 생기면, 특정 동작 실행하도록 설정하는 역할
- 리네 소스코드 추가, 변경 발생시 다시 빌드하는 용도
  <br/>
  <br/>

<strong>설치 확인 위해 버전 확인</strong>
<br/>

<code>brew install watchman</code>
<br/>
<br/>

<strong>설치 확인 위해 버전 확인</strong>
<br/>
<code>watchman --version</code>
<br/>
<br/>

## 리네 및 CLI 설치

<strong>설치 명령어</strong>

<code>npm install -g react-native-cli</code>

<br/>

<strong>설치 확인 위해 버전 확인</strong>
<br/>

<code>npx react-native --version</code>
<br/>
<br/>

## XCode 설치

앱 스토어에서 다운

<br />

This is a new [**React Native**](https://reactnative.dev) project, bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

# Getting Started

> **Note**: Make sure you have completed the [React Native - Environment Setup](https://reactnative.dev/docs/environment-setup) instructions till "Creating a new application" step, before proceeding.

## Step 1: Start the Metro Server

First, you will need to start **Metro**, the JavaScript _bundler_ that ships _with_ React Native.

To start Metro, run the following command from the _root_ of your React Native project:

```bash
# using npm
npm start

# OR using Yarn
yarn start
```

## Step 2: Start your Application

Let Metro Bundler run in its _own_ terminal. Open a _new_ terminal from the _root_ of your React Native project. Run the following command to start your _Android_ or _iOS_ app:

### For Android

```bash
# using npm
npm run android

# OR using Yarn
yarn android
```

### For iOS

```bash
# using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is set up _correctly_, you should see your new app running in your _Android Emulator_ or _iOS Simulator_ shortly provided you have set up your emulator/simulator correctly.

This is one way to run your app — you can also run it directly from within Android Studio and Xcode respectively.

## Step 3: Modifying your App

Now that you have successfully run the app, let's modify it.

1. Open `App.tsx` in your text editor of choice and edit some lines.
2. For **Android**: Press the <kbd>R</kbd> key twice or select **"Reload"** from the **Developer Menu** (<kbd>Ctrl</kbd> + <kbd>M</kbd> (on Window and Linux) or <kbd>Cmd ⌘</kbd> + <kbd>M</kbd> (on macOS)) to see your changes!

   For **iOS**: Hit <kbd>Cmd ⌘</kbd> + <kbd>R</kbd> in your iOS Simulator to reload the app and see your changes!

## Congratulations! :tada:

You've successfully run and modified your React Native App. :partying_face:

### Now what?

- If you want to add this new React Native code to an existing application, check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
- If you're curious to learn more about React Native, check out the [Introduction to React Native](https://reactnative.dev/docs/getting-started).

# Troubleshooting

If you can't get this to work, see the [Troubleshooting](https://reactnative.dev/docs/troubleshooting) page.

# Learn More

To learn more about React Native, take a look at the following resources:

- [React Native Website](https://reactnative.dev) - learn more about React Native.
- [Getting Started](https://reactnative.dev/docs/environment-setup) - an **overview** of React Native and how setup your environment.
- [Learn the Basics](https://reactnative.dev/docs/getting-started) - a **guided tour** of the React Native **basics**.
- [Blog](https://reactnative.dev/blog) - read the latest official React Native **Blog** posts.
- [`@facebook/react-native`](https://github.com/facebook/react-native) - the Open Source; GitHub **repository** for React Native.
