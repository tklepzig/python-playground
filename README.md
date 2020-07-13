- Install deps: `pipenv install`
- Install jupyter lab extensions: `pipenv run install_jupyterlab`
- Add package via pip: `pipenv install ...`
- Run command inside pipenv (or run script specified in Pipfile): `pipenv run ...`
- Open interactive pipenv shell: `pipenv shell`
- Open Lab: `pipenv run jupyter lab`

Update python version (to e.g. 3.8):

1. Manually update Pipfile to 3.8
1. `pipenv update --python 3.8`
