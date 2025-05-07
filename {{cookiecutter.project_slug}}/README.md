# {{ cookiecutter.project_name }}

## Rules !

* 📗 Read [python bests practices](https://dev-recipes-dev.snm.snecma/best-practices/python-best-practices/)
* 📘 Read [version and branchs management](https://dev-recipes-dev.snm.snecma/best-practices/version-branche-best-practices/)
* 🚀 Push your project to [GitLab](https://gitlab.sofa.snm.snecma/)
* 💌 If you need help [send a request to the DevLab (YOM)](https://followup.snm.snecma/projects/devlab-support/issues/new) 

_Thank you for reading, you can remove this section 🤓_

## Get started

### Create a virtual environment

```shell
python -m venv venv
```

And the activate it !

On Windows (PowerShell) : `.\venv\Scripts\Activate.ps1`

On Linux : `source venv\bin\activate`

### Compile requirements

```shell
pip install pip-tools
pip-compile --extra=dev
pip-sync
```

### Install project locally

```shell
pip install -e .
```

_You will execute this step after each `pip-sync` commands._

## How-to contribute

If you want to contribute to this project, please the [CONTRIBUTING.md](CONTRIBUTING.md) file.