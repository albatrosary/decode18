# decode18

## hello-angular

```
$ npm install -g @angular/cli
$ ng new hello-angular
$ cd hello-angular
$ ng serve
```

https://github.com/angular/angular-cli/wiki#getting-started

## hello-vue

```
$ npm install -g @vue/cli
$ vue create hello-vue
$ cd hello-vue
$ yarn serve
```

https://github.com/vuejs/vue-cli#quickstart

```
<script scoped>
…
<script>
```

https://vue-loader.vuejs.org/guide/scoped-css.html#mixing-local-and-global-styles

## hello-react

```
$ npm install -g create-react-app
$ create-react-app hello-react
$ cd hello-react
$ yarn start
```

https://github.com/facebook/create-react-app#quick-overview

```
$ yarn eject
$ yarn
```

### change files

#### config/webpack.config.dev.js

```
loader: require.resolve('css-loader'), options: {
  importLoaders: 1,
  modules: true,
  localIdentName: '[name]__[local]___[hash:base64:5]'
},
```

#### config/webpack.config.prod.js

```
loader: require.resolve('css-loader'), options: {
  importLoaders: 1,
  modules: true,
  minimize: true,
  sourceMap: true
},
```

#### App.js

```
// import ‘./App.css’;
import styles from ‘./App.css’;

class App extends Component {
 render() {
  return (
   <div className={styles.App}>
    <img src={logo} className={styles.AppLogo}
```

#### App.css

```
/* .App-logo { */
.AppLogo {
  animation: App-logo-spin infinite 20s linear;
  height: 80px;
}

/* .App-header { */
.AppHeader {
  ackground-color: #222;
height: 150px;
```

https://medium.com/nulogy/how-to-use-css-modules-with-create-react-app-9e44bec2b5c2

## webcomponents

```
$ npm install -g http-server
$ cd webcompoments/ShadowDOM
$ http-server
```

https://www.html5rocks.com/en/tutorials/webcomponents/customelements/
https://www.html5rocks.com/en/tutorials/webcomponents/template/
https://www.html5rocks.com/en/tutorials/webcomponents/imports/
https://www.html5rocks.com/en/tutorials/webcomponents/shadowdom/
