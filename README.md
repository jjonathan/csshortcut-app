# CSShortcut App

> App desenvolvido no curso de CSS [csshortcut](http://csshortcut.teachable.com/courses/144604)

## Stack

- NodeJS : [NodeJS](https://nodejs.org)
- Task Runner: [Gulp](http://gulpjs.com)
- HTML Template Engine: [Pug](https://pugjs.org)
- CSS Preprocessor: [Stylus](http://stylus-lang.com)

## Run the project locally

- 1 - Install [NodeJS](https://nodejs.org)

- 2 - Prepare the environment:

```sh
$ npm install g gulp-cli
```

- 3 - Clone the project and install the dependencies:

```sh
$ git clone https://github.com/jjonathan/csshortcut-app.git
$ cd csshortcut-app
$ npm install
```

- 4 - Run static server and livereload:

```sh
$ gulp server
```

## Folders Structure

    |.
	├── README.md
	├── LICENSE.md
	├── CONTRIBUTING.md
	├── out/
	├── src/
	|   ├── assets/
	|   |   ├── img/
	|   |   ├── scripts/
	|   |   |   └── script.js
	|   |   └── styles/
	|   |       └── style.styl
	|   ├── partials/
	|   |   ├── footer.pug
	|   |   └── header.pug
	|   ├── layouts/
	|   |   └── default.pug
	|   └── index.pug
	├── gulpfile.js
	├── package.json
	├── .editorconfig
	└── .gitignore

## Automatic Tasks

- `$ gulp build`	: Compile, concat and minify all files.
- `$ gulp server` 	: Watch the files to build and start a static server.

## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.

## Contributing
Find on our [roadmap](https://github.com/afonsopacifer/open-source-boilerplate/issues/1) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/afonsopacifer/open-source-boilerplate/blob/master/CONTRIBUTING.md).

## History
See [Releases](https://github.com/afonsopacifer/open-source-boilerplate/releases) for detailed changelog.

## License
[MIT License](https://github.com/afonsopacifer/open-source-boilerplate/blob/master/LICENSE.md)

## Using [Stylus](http://stylus-lang.com/)

* Install [stylus](http://stylus-lang.com/)
* Open your console and ```cd my/project/root/css```
* Run ```stylus -w main.styl -o main.css```

## Using [PUG](https://pugjs.org/api/getting-started.html)
* Install `npm install pug -g`
* Open your console and `cd my/project/root/css`
* Run `pug file.pug -w` (the flag -w is for watch)