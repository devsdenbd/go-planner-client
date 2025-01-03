# go-planner-client

# GoPlanner(Repo: `go-planner-client`)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<p align="center">
  <a href="https://go-planner.netlify.app" target="_blank" style="font-size:50px">Go Planner</a>
</p>

<h4 align="center">Explore World</h4>

<!--

<p align="center">
    <a href="https://reactplay.io" target="blank">View Demo</a>
    ·
    <a href="https://github.com/reactplay/react-play/issues/new/choose">Report Bug</a>
    ·
    <a href="https://github.com/reactplay/react-play/issues/new/choose">Request Feature</a>
</p>
<p align="center">
  <a href="https://gitpod.io/#https://github.com/reactplay/react-play">
  <img
    src="https://gitpod.io/button/open-in-gitpod.svg"
    alt="Open in Gitpod"
  />
</a>
</p>

## 👋 Introducing ReactPlay

<p align="center">
  <img src="src/images/og-image.png" alt="name"/>
</p>

`react-play` is an `open-source` web app that helps you learn ReactJS faster with a hands-on practice model. It is a collection of `ReactJS projects` that you can use to learn ReactJS.

Is that all? Nope. You can also create your projects and share them with the world. The best part is that the ReactJS experts will `review` your project code before it gets part of the `ReactPlay` app. Isn't that a pure WIN-WIN?

## 🔥 Demo

Here is the link to the app. We hope you enjoy it.

> [The ReactPlay app Link](https://reactplay.io)

Who doesn't want motivation and support? Many Thanks to all the Stargazers who have supported this project with stars(⭐). You all are amazing!!!

<a href="https://github.com/reactplay/react-play/stargazers">
  <img src="https://git-lister.onrender.com/api/stars/reactplay/react-play?limit=25" alt="Stargazers repo roster for @reactplay/react-play" />
</a>

Please support the work by giving the repository a ⭐, contributing to it, and/or sponsoring using the `Sponsor` button at the top 😍. You can also follow us on Twitter [@reactplayio](https://twitter.com/reactplayio).

## 🏗️ How to Set up `ReactPlay` for Development?

You may want to set up the `react-play` repo for the following reasons:

- You want to create a new play (A play is a React project) or want to edit an existing play as a contributor. Please check the [Create a Play Guide](https://docs.reactplay.io/How-To-Guides/how-to-create-play) for more details. Also, please check the [Contribution Guide](./CONTRIBUTING.md) to get started.

- You want to contribute to the `react-play` repo in general. Please check the [Contribution Guide](./CONTRIBUTING.md) to get started.

Here is a quick overview of the `react-play` repo setup:

### 🍴 Fork and Clone the Repo

First, you need to fork the `react-play` repo. You can do this by clicking the `Fork` button on the top right corner of the repo. If you are new to forking, please watch this [YouTube Guide](https://www.youtube.com/watch?v=h8suY-Osn8Q) to get started.

Once forked, you can clone the repo by clicking the `Clone or Download` button on the top right corner of the forked repo.

Please change the directory after cloning the repository using the `cd <folder-name>` command.

> **Note:** Please do not remove the `.env.development` file from the root folder. It contains all the environment variables required for development.

### ⬇️ Install Dependencies

Next, install the dependencies by running the following command in the `react-play` repo. we recommend using `yarn` but you can install using `npm` too

```bash
yarn install
```

Or
```
npm install
```

if you don't have `yarn` installed on your PC, follow the steps below to install it..

**Windows**
1. open your command prompt as administrator.
2. write `corepack enable` and hit enter.
3. then `npm install --global yarn`

**Linux**
1. open terminal and hit `npm install --global yarn`

**MacOS**
1. open terminal and hit `npm install --global yarn`
or
`brew install yarn`

**Or Download Package**
If you are unable to install yarn following the above-mentioned process, then you can simply download the package and install it. Visit the official website of Yarn; there you can just expand the "Alternative" section and it will ask for the version to download for Windows, Linux, or Mac.
`https://classic.yarnpkg.com/en/docs/install#windows-stable`


> **Note**: `ReactPlay` runs on React 18. However, some of our dependencies are yet to upgrade to version 18. So please use the following command when you face difficulties installing the dependencies. Also, ensure to use Node.js version >= 16.x

```
npm install --legacy-peer-deps
```


### 🦄 Start the Development Mode

Use the following command to start the app in the development mode:

```bash
yarn start
```
or if you installed dependencies using ``npm`` use below command

```
npm start
```

**Note**: The `start` script automatically invokes "linters" process. Should you need to run the app without `lint` the use `start:nolint` instead.
However make sure that you run `start` script at least once before committing your code. Code with linter error may not be reviewed.

It runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes. You may also see any lint errors in the console.

### ✨ Format and lint the code

Use the following command to format and lint the code:

#### Format the code

```bash
yarn run format
```
OR
```
npm run format
```

#### Lint the code
*to check the linting issue*
```bash
yarn run lint
```
OR
```
npm run lint
```
*to fix the linting issue*
```bash
yarn run lint:fix
```
OR
```
npm run lint:fix
```

### 🧱 Build the App for Production

Use the following command to build the app for production:

```bash
yarn build
```
OR
```
npm build
```

It builds the app for production to the `build` folder. It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes.

--------------------------------------------------------------

### 🧪 Test App Locally (E2E with Playwright)

Use the following command to install browser(s) binaries to test locally:
```bash
yarn install playwright
```
OR
```
npm install playwright
```

Use the following command to run Playwright tests:

```bash
yarn e2e
```
OR
```
npm run e2e
```
👀 Read more about testing in [react-play](../react-play/e2e/README.md)

👀 Read more about playwright: https://playwright.dev/

--------------------------------------------------------------


### 🚀 Deploy

You can deploy the app to `Vercel` or `Netlify` with a single click.

<a href="https://vercel.com/new/project?template=https://github.com/reactplay/react-play">
<img src="https://vercel.com/button" height="37.5px" />
</a>
<a href="https://app.netlify.com/start/deploy?repository=https://github.com/reactplay/react-play">
<img src="https://www.netlify.com/img/deploy/button.svg" height="37.5px" />
</a>

## 🤝 Contributing to `ReactPlay`

Any kind of positive contribution is welcome! Please help us to grow by contributing to the project.

If you wish to contribute, you can,

- Create a Play
- Suggest a Feature
- Test the app, and help it improve.
- Improve the app, fix bugs, etc.
- Improve documentation.
- Create content about ReactPlay and share it with the world.

> Please read [`CONTRIBUTING`](CONTRIBUTING.md) for details on our [`CODE OF CONDUCT`](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us.

🆕 New to Open Source? 💡 Follow this [guide](https://opensource.guide/how-to-contribute/) to jumpstart your Open Source journey 🚀.

## Launching reactplay Rewards

Contributed to reactplay? Here is a big thank you from our community to you.
Claim your badge and showcase them with pride.
Let us inspire more folks !

![reactplay Badges](https://aviyel.com/assets/uploads/rewards/share/project/43/512/share.png)

### **[Claim Now!](https://aviyel.com/projects/43/reactplay/rewards)**

## 🙏 Support

We all need support and motivation. `ReactPlay` is not an exception. Please give this project a ⭐️ to encourage and show that you liked it. Don't forget to leave a star ⭐️ before you move away.

If you found the app helpful, consider supporting us with a coffee.

<a href="https://www.buymeacoffee.com/greenroots">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50px">
</a>

---

<h3 align="center">
A ⭐️ to <b>ReactPlay</b> is to make us more 💪 stronger and motivated.
</h3>

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!--
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://tapasadhikary.com"><img src="https://avatars.githubusercontent.com/u/3633137?v=4?s=100" width="100px;" alt="Tapas Adhikary"/><br /><sub><b>Tapas Adhikary</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=atapas" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/nirmalkc"><img src="https://avatars.githubusercontent.com/u/6359059?v=4?s=100" width="100px;" alt="Nirmal Kumar"/><br /><sub><b>Nirmal Kumar</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=nirmalkc" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://murtuzaali-surti.me"><img src="https://avatars.githubusercontent.com/u/68743212?v=4?s=100" width="100px;" alt="Murtuzaali Surti"/><br /><sub><b>Murtuzaali Surti</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=murtuzaalisurti" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/abhishek-gogroup"><img src="https://avatars.githubusercontent.com/u/87639443?v=4?s=100" width="100px;" alt="Abhishek Khatri"/><br /><sub><b>Abhishek Khatri</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=abhishek-gogroup" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://abhishek-90.github.io/My-Portfolio/"><img src="https://avatars.githubusercontent.com/u/43419831?v=4?s=100" width="100px;" alt="Abhishek Holani"/><br /><sub><b>Abhishek Holani</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=Abhishek-90" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://hasnainmakada-99.github.io"><img src="https://avatars.githubusercontent.com/u/82728823?v=4?s=100" width="100px;" alt="Hasnain Makada"/><br /><sub><b>Hasnain Makada</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=hasnainmakada-99" title="Code">💻</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://twitter.com/shrilakshmihg"><img src="https://avatars.githubusercontent.com/u/29778698?v=4?s=100" width="100px;" alt="Shrilakshmi Shastry"/><br /><sub><b>Shrilakshmi Shastry</b></sub></a><br /><a href="https://github.com/reactplay/react-play/commits?author=shrilakshmishastry" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>
-->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!--
This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind are welcome!


