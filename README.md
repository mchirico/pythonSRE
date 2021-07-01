[![Build Status](https://dev.azure.com/mchirico/python/_apis/build/status/mchirico.python?branchName=develop)](https://dev.azure.com/mchirico/python/_build/latest?definitionId=29&branchName=develop)
![Python application](https://github.com/mchirico/python/workflows/Python%20application/badge.svg)
[![codecov](https://codecov.io/gh/mchirico/python/branch/develop/graph/badge.svg)](https://codecov.io/gh/mchirico/python)

# python

This is a Python starter project.

```bash
python3 -m venv ~/pythonSRE
source ~/pythonSRE/bin/activate
pip install -r requirements.txt



pip install pycodestyle
pip install --upgrade pycodestyle

```




Use python discover test
```

```


# If you need to reset main

```bash
git checkout --orphan temp_branch
git add .gitignore
git add -A
git rm -r --cached vendor
git commit -am "After squash starting point"

git branch -D main
git branch -m main

git push -f origin main
```

