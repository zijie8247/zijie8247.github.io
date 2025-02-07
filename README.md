

![Github Forks](https://img.shields.io/github/forks/zijie8247/zijie8247.github.io?style=flat)
![Github Stars](https://img.shields.io/github/stars/zijie8247/zijie8247.github.io?style=flat)
![License](https://img.shields.io/github/license/zijie8247/zijie8247.github.io)
![Last Commit](https://img.shields.io/github/last-commit/zijie8247/zijie8247.github.io)

# A simple Github Pages template for academic personal website.

## Preview
[![Screenshot of the Website](https://raw.githubusercontent.com/zijie8247/zijie8247.github.io/master/screenshot_full.png)](https://zijie8247.github.io/)


## Introduction

This is an academic personal website template based on [bootstrap](https://github.com/StartBootstrap/startbootstrap-new-age).

The template is designed to integrate Markdown files as content input.  There's no need to compile the webpage before deployment.  Upon loading, the Markdown files are automatically parsed and embedded into the page.

This template supports LaTeX formula input. You can use `$...$` and `\(...\)` as delimiters for inline-math, or use `$$...$$` and `\[...\]` as delimiters for display-math. Macros such as `\ref{...}`, `\eqref{...}`, and `\begin{equation}...\end{equation}` are also supported. See [MathJax](https://docs.mathjax.org/en/latest/index.html) for more details.

:milky_way: Demo: https://zijie8247.github.io/


## Getting Start
### 1. Fork this repository
The repository name should be `<username>.github.io`, which will also be your website's URL.


### 2. Edit page content

(1) Go to the folder where you want to store your project, and clone the new repository:
```
git clone https://github.com/<username>/<username>.github.io.git
```
The directory structure is as follows:

```.
.
├── contents
└── static
    ├── assets
    │   └── img
    ├── css
    └── js
```

(2) Modify the content of each section, which corresponds to `contents/*.md`.

(3) Adjust the title, copyright information, and other text of the website in `contents/config.yml`

(4) Replace background image and photo with new ones for your web pages in `static/assets/img/`

(5) Push it: 
```
git commit -am 'init'
git push
```


### 3. Enjoy

Fire up a browser and go to `https://<username>.github.io`



## License

Copyright (c) 2023-2024 Sen Li

Copyright (c) 2025 Zijie Wang

Licensed under the MIT license. You can copy, modify, and distribute this template under the same terms.

## Reference

https://github.com/senli1073/senli1073.github.io/
