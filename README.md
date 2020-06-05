<h1 align="center">
    <img alt="Next Level Week" src="https://drive.google.com/file/d/16Byq4aMf2SlELCeLqq0UqNCT3M0cvHDL/view" />
    <br>
    Next Level Week - Ecoleta
</h1>

<h4 align="center">
  A FullStack App that allows users to register and consume points to collect especific recyclable items.
</h4>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/RenBertoldo/Ecoleta-nlw.svg">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/RenBertoldo/Ecoleta-nlw.svg">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/RenBertoldo/Ecoleta-nlw.svg">
  <a href="https://github.com/RenBertoldo/Ecoleta-nlw/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/RenBertoldo/Ecoleta-nlw.svg">
  </a>

  <a href="https://github.com/RenBertoldo/Ecoleta-nlw/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/RenBertoldo/Ecoleta-nlw.svg">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/RenBertoldo/Ecoleta-nlw.svg">
</p>

<p align="center">
  <a href="#technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :technologies:

This project was developed at the [RocketSeat Next Level Week #1](https://nextlevelweek.com/) with the following technologies:

- [KnexJS](http://knexjs.org/)
- [NodeJS](https://nodejs.org)
- [ReactJS](https://reactjs.org/)
- [ExpressJS](https://expressjs.com/)
- [Typescript](https://www.typescriptlang.org/)
- [React Native](https://facebook.github.io/react-native/)
- [react-leaflet](https://react-leaflet.js.org/)
- [react-dropzone](https://react-dropzone.js.org/)
- [react-navigation](https://reactnavigation.org/)
- [SQLite](https://www.sqlite.org/)
- [Axios](https://github.com/axios/axios)
- [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]
- And another bunch of packages....

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v12.17][nodejs] or higher + [Yarn v1.22][yarn] or higher installed on your computer.

From your command line:

```bash
# Clone this repository
$ git clone https://github.com/RenBertoldo/Ecoleta-nlw/

# Go into the repository
$ cd Ecoleta-nlw

# Install dependencies for the backend
$ cd server
$ yarn

# Run migrations and seed to your database
$ yarn knex:migrate && yarn knex:seed 

# Run the backend server
$ yarn dev

# Install dependencies for the frontend and run the server
$ cd frontend
$ yarn 
$ yarn start

# Install dependencies for the mobile
$ cd mobile
$ yarn

# Start React Native Server
$ yarn start

# Run the app (iOS)
$ yarn ios

# Run the app (Android)
$ yarn android
```

## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/RenBertoldo/Ecoleta-nlw/blob/master/README.md) for more information.


[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint