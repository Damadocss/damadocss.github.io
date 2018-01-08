# A Dama do CSS

> 🏹🗡🛡 A blog about Front-end developer by [Simone Amorim](https://simoneas02.github.io/) 💁‍♀️


## Run the project local

**0 -** install the basic dependencies

- [NodeJS](https://nodejs.org/en/)
- [Yarn](https://yarnpkg.com/pt-BR/)
- [Git](https://git-scm.com/)


**1 -** Clone the project and install the dependencies:

```sh
$ git clone https://github.com/damadocss/damadocss.github.io.git
$ cd damadocss.github.io/
$ npm install hexo-cli -g
$ yarn install
```
**2 -** Run the local server:

```sh
$ hexo serve
```

Go to: [localhost:4000](http://localhost:4000)


## Stack

I'm using Hexo for develop this blog, [see documentation](https://hexo.io/pt-br/docs/)!
Using [BEM like nomenclature pattern](http://getbem.com/introduction/) and [ITCSS like architecture pattern](https://speakerdeck.com/dafed/managing-css-projects-with-itcss)


## Folders Structure

	.
	├── scaffolds/
	├── source/
	|   └── _posts
	├── themes
	|   └── css-blog/
	|       ├── languages/
	|       ├── layout/
	|       |   └── partial/
	|       ├── scripts/
	|       ├── source/
	|       |   └── assets/
	|       |       ├── icon/
	|       |       ├── img/
	|       |       └── styles/
	|       └── _config.yml
	├──  _config.yml
	├── .gitignore
	├── package.json
	├── CONTRIBUTING.md
	├── LICENSE.md
	└── README.md


## Versioning

To keep better organization of releases we follow the [Semantic Versioning 2.0.0](http://semver.org/) guidelines.	


## Contributing

Find on our [issues](https://github.com/damadocss/damadocss.github.io/issues/) the next steps of the project ;)
<br>
Want to contribute? [Follow these recommendations](https://github.com/damadocss/damadocss.github.io/blob/dev/CONTRIBUTING.md).

## License

[MIT License](https://github.com/damadocss/damadocss.github.io/blob/dev/LICENSE.md) © [Simone Amorim](https://simoneas02.github.io)
