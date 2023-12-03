# my personal enviroment setup


### git
```
git config --global user.name "JoelcioMatias"
&& git config --global user.email joelcio_psx@hotmai.com
```

### node & nvm

```
https://github.com/nodesource/distributions
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash

nvm ls-remote
nvm use 16.20.2
```


### ambiente jupyter
```
conda create --name  jupyter-env python=3.10
& conda activate jupyter-env
& pip install ipykernel
& python -m ipykernel install --user --name=jupyter-env
```


