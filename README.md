<p align="center">
<a href="https://grzegorz-jodlowski.github.io/golden-studio/"><img src="images/logo3.jpg" title="logo" alt="title with text It's nice to meet you"></a>
</p>



# <p align="center">👓 Golden studio</p>
<p align="center">Project for learning advanced CSS, Node Package Manager and GIT</p>

</br>

## Table of Contents

- [What's this project about?](#about)
- [Technologies used](#tech)
- [What I learned?](#what)
- [Interesting code snippet](#interesting)
- [Installation](#install)
- [NPM scripts](#scripts)
- [Website (on GitHub Pages)](#site)

</br>

## <a name="about"></a>What's this project about?

 This is website for creative agency written to learn webdevelopment tools.
 It contains menu, modal, services section, portfolio, and footer.

</br>

## <a name="tech"></a>Technologies used
- HTML
- CSS
- SCSS
- Bootstrap
- npm
- GIT

</br>

## <a name="what"></a>What I learned?
- create and customize development environment,
- set the correct directory structure,
- use many useful shortcuts when working in VS code,
- use additional VS code extensions,
- work with the terminal in a more advanced way,
- set up github repositories and authenticate with the SSH key,
- use version control system in an advanced way (see the project for learning GIT <a href="https://github.com/grzegorz-jodlowski/git-learning-2">here</a>),
- use the Node Package Manager in my projects (also pros and cons of using it),
- search for useful packages in the project,
- create tusk runner using npm (being aware of the alternatives e.g. Grunt, Gulp, WebPack),
- download the gitignore file automatically from GitHub,
- work with a JSON file

</br>

## <a name="interesting"></a>Interesting code snippet (for me of course 😉)
- using the npm-run-all package and download the gitignore file automatically from GitHub,

```JSON
"scripts": {
    "init-project": "npm install && npm-run-all init:*",
    "init:dirs": "mkdirp sass css vendor images js",
    "init:files": "touch README.md index.html sass/style.scss js/script.js",
    "init:gitignore": "curl https://raw.githubusercontent.com/github/gitignore/master/Node.gitignore -o .gitignore",
    ...
    ...
```


</br>

## <a name="install"></a>Installation and quick start

- use the package manager [npm](https://www.npmjs.com/get-npm) to install dependencies:

```bash
npm install

or

npm i
```
- run watch mode to start the server, constantly refreshing and more:

```bash
npm run watch
```

<br/>


## <a name="scripts"></a>NPM scripts

There are 3 main scripts to speed up work:

- `build`: builds a project,
- `watch`: observes changes and starts working preview,
- `test`: starting the tests of html and CSS structure,

<br/>

## <a name="site"></a>Website (on GitHub Pages)
<a href="https://grzegorz-jodlowski.github.io/golden-studio/">Golden studio</a>

</br>
</br>

  *project implemented as part of the 9-month [Web Developer Plus](https://kodilla.com/pl/bootcamp/webdeveloper/?type=wdp&editionId=309) course organized by [Kodilla](https://drive.google.com/file/d/1AZGDMtjhsHbrtXhRSIlRKKc3RCxQk6YY/view?usp=sharing)


