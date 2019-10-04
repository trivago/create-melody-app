# Create Melody App

Create Melody apps quickly from the command line

## Installation

### npm
```sh
npm i -g create-melody-app
```

### yarn
```sh
yarn global create-melody-app
```

## Creating an app

The suggested versions are Node 8.16.0 or Node 10.16.0 or later version on your local development machine.

```sh
create-melody-app my-app
```

It will create a directory called my-app inside the current folder.
Inside that directory, it will generate the initial project structure:

```
my-app
├── package.json
├── webpack.condif.js
├── yarn.lock
├── .gitignore
├── public
│   ├── index.html
│   └── main.css
└── src
    ├── counter
    │   ├── index.js
    │   └── index.twig
    ├── home
    │   ├── index.js
    │   └── index.twig
    └── index.js
```

Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm i` or `yarn`

Install the transitive dependencies

### `npm start` or `yarn start`

Runs the app in development mode

### `npm run build` or `yarn build`

Builds the app for production to the build folder

## License
This project is released under the terms of the [Apache 2.0 license](http://www.apache.org/licenses/LICENSE-2.0).
