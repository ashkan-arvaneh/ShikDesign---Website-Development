# website

> New ShikDesign website with Nuxt.js and Vue.js

Shik Design is an experienced web development agency dedicated to creating practical, distinctive business websites and web applications. From the start our aim has been to provide simple, end-user-driven solutions for a sensible, fixed price. (http://www.shikdesign.co.uk/)


## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).


# Project Structure
.
├── assets/                     # contains un-compiled assets such as LESS, SASS or JavaScript
│   └── ...
├── components/
│   ├── header.vue              # contains Vue.js Components.
│   └── ...
├── pages/						# contains Application Views and Routes.
│   ├── index.vue 
│   └── ... 
├── static/                     # contains static files. Each file inside this directory is mapped to /.
│								  Example: /static/robots.txt is mapped as /robots.txt
├── .nuxt.config.js             # contains Nuxt.js custom configuration.
├── .eslintrc.js                # eslint config
├── .editorconfig               # editor config
└── package.json                # build scripts and dependencies