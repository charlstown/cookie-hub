# Site Template

[![mkdocs](https://img.shields.io/badge/mkdocs-{{ cookiecutter.mkdocs_version }}-blue)](https://www.mkdocs.org/)
[![template](https://img.shields.io/badge/template-material-dd2e57)](https://squidfunk.github.io/mkdocs-material/)
[![license](https://img.shields.io/badge/license-{{ cookiecutter.license }}-green.svg?logo=cachet&style=flat&logoColor=green)](LICENSE)

This is a multipurpose template for creating a wide range of websites, from personal sites and blogs to corporate sites and online communities. With this template, you can easily get started on your project and have a professional-looking website up and running in no time.


Features:

- Modern and clean design
- Fully responsive and mobile-friendly
- Easy to customize and extend
- Built with the latest web technologies
- Compatible with a wide range of browsers
- Cross-platform support
- SEO-friendly
- Accessible and inclusive


This template includes all the essential features you need to create a website that meets your specific needs. Whether you're a developer, designer, blogger, entrepreneur, or someone who just wants to have an online presence, this template has got you covered.

</br>

<details><summary><b>Readme contents</b></summary>

- [1. Description](#1-Description)
- [2. Installation](#2-Installation)
- [3. Usage](#3-Usage)
- [4. Troubleshooting](#4-Troubleshooting)
- [5. Disclaimer](#5-Disclaimer)
- [6. Help wanted](#6-Help-wanted)
- [7. Other links](#7-Other-links)

</details>

</br>

*Repository url:* https://github.alm.europe.cloudcenter.corp/cib-gluon/gluon-community-portal

---

## 1. Description

This repository contains the source code for a community portal website built using mkdocs and the material theme. The focus of the site is to serve as a central hub for the Gluon community, providing resources, support, and a platform for engagement and collaboration among members.

## 2. Installation

Get started with your local installation of the Gluon community portal by following the next step-by-step guide.

### 2.0 (optional) Setup pypi as trusted host permanently

Before installing the environments, as an optional step but very recommended, you can set pypi as a trusted host by running the following commands.

(Optional) You can locate your ``pip.ini`` files by running this command
```bash
$ pip config -v list
# ouput:
For variant 'global', will try loading 'C:\ProgramData\pip\pip.ini'
For variant 'user', will try loading 'C:\Users\user\pip\pip.ini'
For variant 'user', will try loading 'C:\Users\user\AppData\Roaming\pip\pip.ini'
For variant 'site', will try loading 'C:\Users\user\root_to_virtual_environment\pip.ini'
```

To set pypi as trusted host run the next command:
```bash
pip config set global.trusted-host "pypi.org files.pythonhosted.org pypi.python.org"
```

### 2.1 Creating an environment in Virtualenv

**1. Open the terminal:** After you have installed vistualenv, open the gitbash terminal.

**2. Create a virtual environment:** Run the following command:
```
virtualenv [environment_name]
```
in your terminal or command prompt, replacing [environment_name] with the name you want to give your virtual environment. For example an environment called "gluoncommunity".

**3. Activate the virtual environment:** On Windows, run 
```
[environment_name]\Scripts\activate
```
On macOS or Linux, run
```
source [environment_name]/bin/activate
```

**4. Deactivate the virtual environment:** When you are finished working in your virtual environment, you can deactivate it by running deactivate in your terminal or command prompt.


### 2.2 Creating an environment in Conda

**1. Open the terminal:** After you have installed conda, open the terminal to access the conda command line interface.

**2. Create an environment:** To create an environment, type the following command in the terminal:
```
conda create --name env_name python=x.x
```
 where env_name is the name you want to give to your environment and x.x is the version of Python you want to install in the environment. For example, if you want to create an environment called "gluoncommunity" with Python 3.7, the command will be:
 ```
 conda create --name myenv python=3.7.
 ```

**3. Activate the environment:** After the environment has been created, you need to activate it. To activate the environment, type the following command in the terminal: 
```
conda activate env_name
```
where env_name is the name of the environment you just created.

**4. Deactivate the environment:** When you are done using the environment, you can deactivate it. To deactivate the environment, type the following command in the terminal: conda deactivate.

## 3. Usage

To serve the Gluon community site you need to follow these steps:

1. Activate the virtual environment.
2. Install the requirements for the project by running the command
    ```
    pip install -r requirements.txt
    ```

    Remember that if you don't have set the pypi as trusted host globally you can add the following flags to the previous command.
    ```
    pip install --trusted-host pypi.org --trusted-host pypi.python.org --trusted-host files.pythonhosted.org -r requirements.txt
    ```

3. For next command make sure you are in the directory of the repository.
    ```
    cd gluon-community-portal
    ```
4. Run the command
    ```
    mkdocs serve -w material/overrides/
    ```
    to serve the site locally.
5. Make modifications to the site as needed in the material/overrides/ directory. The site will automatically update with the changes as you make them.

## 4. Troubleshooting

If you encounter any issues while using this repository, check the following for solutions:

- Check the environment and requirements.
- Verify the configuration files.
- Try restarting the server.
- Check the logs for errors.
- Try a different browser or device.
- Check for known issues or solutions in the documentation.
- Open a GitHub issue if no solution is found.

If you still cannot find a solution, you can open an issue on the repository's GitHub page for further assistance.

## 5. Disclaimer

The contents of this website are for informational purposes only and should not be construed as professional advice. The information provided by Santander is not guaranteed to be accurate, complete or up-to-date. Use of the information provided is at your own risk. Santander assumes no responsibility or liability for any errors or omissions in the information provided.

## 6. Help wanted

Looking for ways to contribute? Check out our open issues and help us build a better community portal! If you have any questions, feel free to open an issue.

## 7. Other links

References, contact or related repositories go here.
