1. Install pipx https://pypi.org/project/pipx/
2. Install Virtualenv https://virtualenv.pypa.io/en/latest/index.html - Everything is done inside virtualenv
3. Create new env using virtualenv --python=python3.6 $VIRTUAL_ENV
This will add python 3.6 virutal env to poetry virtual envs director. On macOs probably in /Users/<user>/Library/Caches/pypoetry/virtualenvs/

# Publishing
```
python3 -m pip install --user --upgrade setuptools wheel
python3 setup.py sdist bdist_wheel
python3 -m twine upload dist/*
```