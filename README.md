# google-adk-learning

Learn Google Agent Development Kit (ADK)

## Python Environment

Install `pyenv`.

```
bash $ curl -fsSL https://pyenv.run | bash
```

Add to `.bashrc`.

```
bash $ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc
bash $ echo '[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc
bash $ echo 'eval "$(pyenv init - bash)"' >> ~/.bashrc
```

Edit `.bash_profile`.

```
bash $ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bash_profile
bash $ echo '[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile
bash $ echo 'eval "$(pyenv init - bash)"' >> ~/.bash_profile
```

Restart shell.

```
bash $ exec "$SHELL"
```

Install python 3.12.5 for default environment.

```
bash $ pyenv install 3.12.5
bash $ pyenv shell 3.12.5
bash $ pyenv virtualenv adk
```

## Use the Environment

```
bash $ pyenv activate adk
```

## Install Google-ADK

```
bash $ pip install google-adk
```

