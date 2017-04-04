# CSShortcut App

> App desenvolvido no curso de CSS [csshortcut](http://csshortcut.teachable.com/courses/144604)

## Stack

- Task Runner: [Gulp](http://gulpjs.com)
- HTML Template Engine: [Pug](https://pugjs.org)
- CSS Preprocessor: [Stylus](http://stylus-lang.com)

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
	|   |   |   └── script.
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