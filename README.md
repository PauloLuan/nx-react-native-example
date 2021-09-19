## 💡 Introduction

This is a monorepo for my studies and ideas related to React Native.

<span id="top"></span>

<p align="center">
    <a href="#"><img src="https://github.com/pauloluan/assets/blob/master/back.png?raw=true" width="100"></a>
</p>

<p align="center">
    <a href="https://github.com/PauloLuan/rn-playground/actions/workflows/ci.yml"><img src="https://img.shields.io/github/workflow/status/pauloluan/rn-playground/CI Checks?style=for-the-badge"></a>
    <a href="https://github.com/PauloLuan/rn-playground/actions/workflows/ci.yml"><img src="https://forthebadge.com/images/badges/it-works-why.svg"></a>
</p>

## 📝 Minimal Requirements

- NodeJs 14.x

## 🚀 Install

```sh
$ git clone https://github.com/PauloLuan/rn-playground.git
```

```sh
$ yarn
```

### Running:

to start all apps in parallel:

```sh
$ yarn start
```

### Testing:

```sh
$ yarn test
```
### Create a new app

```
npx nx g nx-react-native-expo:app <app-name>
```

When using Nx, you can create multiple applications and themes in the same workspace. If you don't want to prefix your commands with npx, install `@nrwl/cli` globally.

### Start the bundler

```
npx nx start <app-name>
```

### Run on devices

Android:

```
npx nx run-android <app-name>
```

iOS:

```
npx nx run-ios <app-name>
```

Web:

```
npx nx run-web <app-name>
```

### Build the app

```
npx nx bundle <app-name>
npx nx bundle <app-name> --platform=ios
npx nx bundle <app-name> --platform=android
```

## Using components from React library

You can use a component from React library generated using Nx package for React. Once you run:

```
npx nx g nx-react-native-expo:lib ui-button
```

This will generate the `UiButton` component, which you can use in your app.

```jsx
import { UiButton } from '@myorg/ui-button';
```
## Learn more

It uses [NX](https://nx.dev/) and it helped me to architect, test, and build those apps on the apps folder, visit the [Nx Documentation](https://nx.dev) to learn more.
## 👤 Paulo Luan

Where you can find me:

<p align="center">
  <a href="http://bit.ly/pauloluan-insta">
    <img src="https://github.com/pauloluan/assets/blob/master/insta.png" width="50"  alt="Follow me on Instagram" />
  </a>
  <a href="https://bit.ly/pauloluan/">
    <img src="https://github.com/pauloluan/assets/blob/master/linkedin.png?raw=true" width="50" alt="Follow me on Linkedin" />
  </a>
  <a href="https://github.com/pauloluan">
    <img src="https://github.com/pauloluan/assets/blob/master/github.png?raw=true" width="50"  alt="Follow me on Github" />
  </a>
</p>

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/pauloluan/rn-playground/issues).

## Show your support

Give a ⭐️ if this project helped you!

[![standard][standard-image]][standard-url] [![forthebadge][works-on-my-machine-image]][works-on-my-machine-url]

[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=for-the-badge
[standard-url]: http://npm.im/standard
[works-on-my-machine-image]: https://forthebadge.com/images/badges/works-on-my-machine.svg
[works-on-my-machine-url]: https://forthebadge.com

[🔝 back to top](#top)
