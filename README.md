# datafun-04-jupyter
P4: Presenting Data Stories with Jupyter

## CC4.1: Start a New Project

### Clone Your Repo

```shell
git clone "paste_your_repo_URL_here"
```

### Create Project Virtual Environment

On Windows, create a project virtual environment in the .venv folder. 

```shell
py -m venv .venv
.venv\Scripts\Activate
pip list
py -m pip install --upgrade pip
py -m pip install -r requirements.txt
deactivate
```

### Create files in root folder

```shell
# Example for managing project requirements
code .
ni "requirements.txt"
```

### Git add and commit 

```shell
git add .
git commit -m "initial commit"
git push origin main
```