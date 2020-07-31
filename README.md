<h1 align="center">
    <img alt="DevRadar" title="#delicinha" src=".github/logo.svg" width="250px">
</h1>
<!-- #8262E7 -->
<h4 align="center">
  🚀 Connect with other Devs
</h4>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/EliasGcf/dev-radar?color=%238262E7">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/EliasGcf/dev-radar?color=%238262E7">

  <a href="https://github.com/EliasGcf/dev-radar/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/EliasGcf/dev-radar?color=%238262E7">
  </a>

  <a href="https://github.com/EliasGcf/dev-radar/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/EliasGcf/dev-radar?color=%238262E7">
  </a>

  <a href="https://github.com/EliasGcf/dev-radar/blob/master/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=%238262E7">
  </a>
</p>

<p align="center">
  <a href="#-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

<p id="insomniaButton" align="center">
  <a href="https://insomnia.rest/run/?label=&uri=" target="_blank">
    <img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia">
  </a>
</p>

<p align="center">
  <img alt="Frontend" src=".github/devradar.png" width="100%">
</p>

## 💻 About the project

DevRadar it is an application to connect developers who are close to each other.

## 🚀 Technologies

Technologies that I used to develop this application

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)

## 💻 Getting started

Import the `Insomnia.json` on Insomnia App or click on [Run in Insomnia](#insomniaButton) button.

### Requirements

- [Node.js](https://nodejs.org/en/)
- [MongoDB](https://www.mongodb.com/)
- [Yarn](https://yarnpkg.com/) ou [npm](https://www.npmjs.com/)
- [Expo](https://expo.io/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/EliasGcf/dev-radar && cd dev-radar
```

**Follow the steps below**

### Backend

```bash
# Starting from the project root folder, go to backend folder
$ cd backend

# Install the dependencies
$ yarn

# Edit the src/index.js and put the MongoDB URL connection

# To finish, run the api service
$ yarn dev

# Well done, project is started!
```

### Web

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to frontend folder
$ cd frontend

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.js' have the IP to your API

# Start the client
$ yarn start
```

### Mobile

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.js' have the IP to your API

# Run the command to start expo bundle
$ yarn start

# Now choose your option to install the app
```

## 🔖 Layout

You can download the project layout on `.sketch` format [here](.github/DevRadar.sketch).

Also, it is possible use [Figma](https://figma.com) to open `.sketch` files on any operating system.

## 🤔 How to contribute

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork EliasGcf/dev-radar
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url && cd dev-radar

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜 &nbsp;by Elias Gabriel 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/eliasgcf/)
