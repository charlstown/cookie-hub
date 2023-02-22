# Site Template

[![mkdocs](https://img.shields.io/badge/mkdocs-1.4-blue)](https://www.mkdocs.org/)
[![template](https://img.shields.io/badge/template-material-dd2e57)](https://squidfunk.github.io/mkdocs-material/)
[![license](https://img.shields.io/badge/license-MIT-green.svg?logo=cachet&style=flat&logoColor=green)](https://opensource.org/licenses/MIT)
[![My Site](https://img.shields.io/badge/about%20me-carlosgrande.me-red?style=flat&logo=aboutdotme&logoColor=red)](https://carlosgrande.me/)

This is a 🍪 cookiecutter multipurpose template for creating a wide range of websites, from personal sites and blogs to corporate sites and online communities. With this template, you can easily get started on your project and have a professional-looking website up and running in no time.

![Logo](docs/assets/images/logo.png)

Features:

- Modern and clean design
- Fully responsive and mobile-friendly
- Easy to customize and extend
- Built with the latest web technologies
- Compatible with a wide range of browsers
- Cross-platform support


This template includes all the essential features you need to create a website that meets your specific needs. Whether you're a developer, designer, blogger, entrepreneur, or someone who just wants to have an online presence, this template has got you covered.

</br>

<details><summary><b>Readme contents</b></summary>

- [1. What is Site Template](#1-what-is-site-template)
- [2. Installation](#2-Installation)
- [3. Usage](#3-Usage)
- [4. Troubleshooting](#4-Troubleshooting)
- [5. Disclaimer](#5-Disclaimer)
- [6. Help wanted](#6-Help-wanted)
- [7. Other links](#7-Other-links)

</details>

</br>

---

## 1. What is Site Template

This is a modern and clean template for MkDocs, built using the Material Design framework. The template is fully responsive and mobile-friendly, making it easy to view your content on any device. It's also easy to customize and extend, so you can make it your own.

Built with the latest web technologies, this template is compatible with a wide range of browsers and has cross-platform support. Whether you're creating a personal site, a blog, documentation, or a corporate site, the MkDocs Material Template is the perfect choice for your project.


## 1.1 What is cookiecutter

A command-line utility that creates projects from cookiecutters (project templates), e.g. creating a Python package project from a Python package project template.

Visit these links to learn more about cookiecutter.
Documentation: https://cookiecutter.readthedocs.io/
GitHub: https://github.com/cookiecutter/cookiecutter


## 1.2 Repository contents

```
site-template                           -> Project directory.
├── cookiecutter.json                   -> Cookiecutter values.
├── {{cookiecutter.repository_name}}    -> Cookiecutter template.
│   └── ...
├── mkdocs.yml                          -> mkdocs configuration file.
├── docs                                -> Project documentation.
│   └── ...
├── README.md                           -> README file.
├── code_of_conduct.md                  -> Code of conduct file.
├── contributing.md                     -> Contributing file.
├── LICENSE                             -> LICENSE file.
└── requirements.txt                    -> Requirements to run the project.
```

</br>

# 2. Installation

To create the project from the template you need to install cookiecutter and follow these instructions.


## 2.1 Cookiecutter installation

Installing cookiecutter package on Ubuntu is very easy, you can simply run the next command to install it.
```
pip install cookiecutter
```

Visit the link to the cookiecutter documentation to learn more about the installation:  
[Install cookiecutter](https://cookiecutter.readthedocs.io/en/stable/installation.html#install-cookiecutter)


## 2.2 Site Template installation

To generate a custom project from the template, follow these steps:
- 1. Navigate to the path where you desire to generate the project folder.
- 2. Run the cookiecutter command followed by the repository URL.
  ```
  python -m cookiecutter https://github.com/charlstown/py-template.git
  ```
- 3. Fill out the form in the console and the project will be generated at the end.

</br>

# 3. Usage

## 3.1 Test run

After setting up the template, you can do a test run.

Serve the site locally running this command.
```
mkdocs serve -w overrides/
```

You may add the flag '-a localhost:8080' to select a custom local port.


## 3.2 Starting to code your project

We recommend starting coding your project with these tips:

CONTENT

</br>

# 4. Troubleshooting

The main branch has been tested and before any push, we make sure everything is working fine.
Feel free to open a new issue if you see the archetype is no working correctly or any additional requirement is needed.

</br>

# 5. Disclaimer

This is an archetype template done in MkDocs using the library cookiecutter. This template is intended to help creating a personal site, a blog, documentation, or a corporate site.

Do not use this template for any commercial nor redistribution purpose. Actually, the use of such tool might be allowed for open-source or private projects.

</br>

# 6. Help Wanted

This repository does provide the required installation instructions to install it by your own.
Feel free to contact me on https://carlosgrande.me/contact-me-carlos-grande/

</br>

# 7. Other links

- [carlosgrande.me](https://carlosgrande.me/)
- [Cookiecutter documentation]( https://cookiecutter.readthedocs.io/)
- [Coockiecutter official repository](https://github.com/cookiecutter/cookiecutter)
- [MkDocs official site](https://www.mkdocs.org/)
- [Material template official site](https://squidfunk.github.io/mkdocs-material/)