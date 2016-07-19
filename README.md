# react-webpack-babel
Simple React Webpack Babel Starter Kit


This is a [React](https://facebook.github.io/react/), [Webpack](http://webpack.github.io/), [Gulp](http://gulpjs.com/), [Materialize](http://materializecss.com/),  [Mongo](https://www.mongodb.com/), and [Babel](https://babeljs.io/) application.
Based directly on: https://github.com/alicoding/react-webpack-babel.git 

### What's in it?

Development files are in src and build directories contain the files created by the [Gulpfile](./gulpfile) for deployment or local hosting.


### To run

* You'll need to have [git](https://git-scm.com/) and [node](https://nodejs.org/en/) installed in your system.
* Fork and clone the project:

```
> $ git clone https://github.com/waltdakind/react-webpack-babel-materialize
```

Then install the dependencies:

```
> $ npm install
```
Install materialize-css:
```
> $ npm install materialize-css
```
Install webpack and the development server:

```
> $ npm i webpack-dev-server webpack -g
```

You can simply run webpack build using this command: 

```
> $ npm run build
```

If you want to run with webpack-dev-server simply run this command: 

```
> $ npm run dev
```
If you want to deply: 

```
> $ npm run deploy   (need to add this to gulpfile)
```
Open the web browser to `http://localhost:8888/`

Please contribute to the project if you think this can be done better in anyway even for this README :)
