# Test template generator

This project aims to be a skeleton to test the setup of a template generator project.

## Install

In order to use the Python application for the rendering of the templates, you need to create a virtualenv with Python 3.7+ and install the requirements like:
```
virtualenv -p /usr/bin/python3.7 venv
source venv/bin/activate
pip install -r ./requirements.txt
```

## Objective

Setup a build process using Webpack / Rollup / ... to generate 2 templates:
 - home.html: which will include a common CSS/JS (common.css, common.js) and a custom one (home.css, home.js)
 - about.html: which will include a common CSS/JS (common.css, common.js) and a custom one (about.css, about.js)

The content of the files are not important

Nice to have: Use a stylesheet language like SASS / LESS / SCSS / ...
