<p align="center">
<a href="https://grzegorz-jodlowski.github.io/golden-studio/"><img src="logo3.jpg" title="logo" alt="title with text It's nice to meet you"></a>
</p>



# <p align="center">👓 Golden studio</p>
<p align="center">Project for learning advanced CSS, Node Package Manager and version control system (GIT)</p>

</br>

## Table of Contents

- [What's this project about?](#about)
- [Technologies used](#technologies)
- [What I learned?](#what)
- [Interesting code snippet](#interesting)
- [GitHub Pages](#gitHub)

</br>

## <a name="about"></a>What's this project about?

 This is website for creative agency written to learn webdevelopment tools.
 It contains menu, modal, services section, portfolio, and footer.

</br>

## <a name="technologies"></a>Technologies used
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

## <a name="gitHub"></a>GitHub Pages
<a href="https://grzegorz-jodlowski.github.io/golden-studio/">Golden studio</a>


