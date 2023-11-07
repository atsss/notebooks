## Build enviroment
1. Install pyenv
> https://github.com/pyenv/pyenv
```
brew install pyenv
which pyenv # check
```
```
// bash_profile
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
```

2. Install python 3.11.3
```
pyenv install 3.11.3
```

3. Set v3.11.3 python as local
```
pyenv local 3.11.3
python --version # check
```

4. Install pipenv
```
pip install pipenv
which pipenv # check
```

5. Install libraries
```
pipenv install
pipenv install --dev
```

6. Run
```
pipenv shell
jupyter lab
```

## Update python
1. Update pyenv
```
brew upgrade pyenv
pyenv install --list # check
```

2. Install python
```
pyenv install 3.x.x
```

3. Set v3.x.x python as local
```
pyenv local 3.x.x
python --version # check
```
