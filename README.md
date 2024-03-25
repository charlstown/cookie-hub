# Cookie Hub

[![mkdocs](https://img.shields.io/badge/mkdocs-1.4-blue)](https://www.mkdocs.org/)
[![template](https://img.shields.io/badge/template-material-dd2e57)](https://squidfunk.github.io/mkdocs-material/)
[![license](https://img.shields.io/badge/license-MIT-green.svg?logo=cachet&style=flat&logoColor=green)](https://opensource.org/licenses/MIT)
[![My Site](https://img.shields.io/badge/about%20me-carlosgrande.me-red?style=flat&logo=aboutdotme&logoColor=red)](https://carlosgrande.me/)

This is a 🍪 cookiecutter multipurpose template for efficient management of user demands and support requests. Easily track bugs, requirements, support, resources needs, and more, all in one convenient location.

**Features:**

:arrow_forward: Issues templates:
  - Bug reports
  - Support requests
  - Requirement submissions
  - Onboarding new members
  - Resource requests

:arrow_forward: Workflows for labeling issues:
  - Automatic labeling based on comment parsing
  - Auto-labeling when an issue is assigned


</br>

<details><summary><b>Readme contents</b></summary>

- [Cookie Hub](#cookie-hub)
  - [1. What is Cookie Hub](#1-what-is-cookie-hub)
  - [1.1 What is cookiecutter](#11-what-is-cookiecutter)
  - [1.2 Repository contents](#12-repository-contents)
- [2. Installation](#2-installation)
  - [2.1 Build repository from template](#21-build-repository-from-template)
- [3. Usage](#3-usage)
  - [3.1 Create labels](#31-install-the-requirements)
  - [3.2 Test the workflow](#32-test-run)
- [4. Troubleshooting](#4-troubleshooting)
- [5. Disclaimer](#5-disclaimer)
- [6. Help Wanted](#6-help-wanted)
- [7. Other links](#7-other-links)

</details>

</br>

---

## 1. What is Cookie Hub

This is a modern and user-friendly template for managing demand and support services within tech teams. Built with flexibility in mind, it offers customizable issue templates for bug reports, support requests, feature requirements, and more. With automated workflows for issue labeling and seamless integration with GitHub.


This template is perfect for various use cases, such as:
- Managing customer feedback and feature requests for software development teams.
- Coordinating service requests and incident reports for IT support teams.
- Organizing project requirements and tracking progress for agile development teams.
- Facilitating communication and collaboration among remote teams working on a shared project.
- Streamlining the onboarding process for new team members by providing a centralized repository of resources and guidelines.


## 1.1 What is cookiecutter

A command-line utility that creates projects from cookiecutters (project templates), e.g. creating a Python package project from a Python package project template.

Visit these links to learn more about cookiecutter.
Documentation: https://cookiecutter.readthedocs.io/
GitHub: https://github.com/cookiecutter/cookiecutter


## 1.2 Repository contents

```
cookie-site                           -> Project directory.
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

To create the project from the template you need to install Python, pip and the cookiecutter python library and follow these instructions.

> **Note**  
> It is recommended to create and activate a virtual environment to install the libraries

## 2.1 Install cookiecutter

To install cookicutter run the following command.

```bash
pip install cookiecutter
```


## 2.2 Build repository from template

To generate a custom project from the template, follow these steps:

1. Navigate to the path where you desire to generate the project folder.
2. Run the cookiecutter command followed by the repository URL.
  ```bash
  python -m cookiecutter https://github.com/charlstown/cookie-hub.git
  ```
3. Fill out the form in the console and the project will be generated at the end.

**:fireworks::raised_hands: Congrats!! you have your project set and ready to roll.**


## 2.3 [Optional] Generate custom labels

We have two types of custom labels for this template, the __type__ and the __status__ of the issue. To create these labels yopu need to run the workflow named __`Create custom labels`__.

- __`type`__: Contains the labels with the type of issue form selected, there is one per issue template.
- __`status`__: Contains the labels with the different status of the issue.

| Label name | color | Description |
|-|-|-|
| `[type] bug` | ![#E99695](https://placehold.co/10x10/E99695/E99695.png) `#E99695` | The group of issues opened as a bug type. |
| `[type] incident` | ![#0052CC](https://placehold.co/10x10/0052CC/0052CC.png) `#0052CC` | The group of issues opened as an incident type. |
| `[type] requirement` | ![#0052CC](https://placehold.co/10x10/0052CC/0052CC.png) `#0052CC` | The group of issues opened as a requirement type. |
| `[type] resource` | ![#0052CC](https://placehold.co/10x10/0052CC/0052CC.png) `#0052CC` | The group of issues opened as a resource type. |
| `[type] onboarding` | ![#0052CC](https://placehold.co/10x10/0052CC/0052CC.png) `#0052CC` | The group of issues opened as an onboarding type. |
| `[status] review` | ![#0E8A16](https://placehold.co/10x10/0E8A16/0E8A16.png) `#0E8A16` | The group of issues that are under review. |
| `[status] awaiting` | ![#FBCA04](https://placehold.co/10x10/FBCA04/FBCA04.png) `#FBCA04` | The group of issues that are awaiting a response from the user. |
| `[status] bloqued` | ![#B60205](https://placehold.co/10x10/B60205/B60205.png) `#B60205` | The group of issues that are bloqued. |

</br>

> **Note**  
> Feel free to add as many custom labels as you need for your project, and new group of labels like teams, organizations, etc. 


</br>

# 3. Usage

## 3.1 Install the requirements

You can install the requirements for the project by running the command
```bash
pip install -r requirements.txt
```

Remember that if you didn't set the pypi as trusted host globally in the previous step, you can add the following flags to the command.
```
pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org -r requirements.txt
```


## 3.2 Test run

After setting up the template, you can do a test run.

Serve the site locally running this command.
```bash
mkdocs serve -w overrides/
```

You may add the flag '-a localhost:8080' to select a custom local port.

## 3.3  Adding the project to a new Github repository

- **Step 1: Create a new repository in github:**

  Create the new repository and make sure you give it the same name of the project folder, in our case my-cool-site.

  > **Warning**
  > Don't add any predefined file from github in the new repository, all the files are included in the local project folder.

- **step 2: Push the local repository:**

  ```bash
  git remote add origin {{LINK TO YOUR EMPTY REPO}}
  git branch -M main
  git push -u origin main
  ```

## 3.3 Starting to code your project

To start coding your project we recommend to understand the project structure.
```
my-cool-site/                   -> Project directory
├── mkdocs.yml                  -> MkDocs configuration file
├── docs/                       -> Pages and site content
│   ├── about/                  -> About section with pages
│   ├── assets/                 -> Global assets for the site
│   │   ├── images              -> Global images for the site
│   │   ├── javascripts         -> Global javascripts for the site
│   │   └── stylesheets         -> Global CSS styles for the site
│   ├── getting-started.md      -> Getting started page
│   └── index.md                -> Home page
├── overrides/                  -> HTML to override material theme
│   ├── home.html               -> HTML for the home page
│   └── main.html               -> HTML for all pages
├── README.md                   -> README file.
├── code_of_conduct.md          -> Code of conduct file
├── contributing.md             -> Contributing file
├── LICENSE                     -> LICENSE file
└── requirements.txt            -> Requirements to run the project
```

### Understand the project structure



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
