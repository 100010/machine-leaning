# Init

```
$ brew install pyenv
$ echo 'eval "$(pyenv init -)"' >> ~/.zshrc
$ pyenv install 3.6.0
$ pyenv rehash
$ pyenv global 3.6.0
$ pip install numpy scipy scikit-learn matplotlib pandas
```


# Trouble shooting

## import somemodule failed
```
RuntimeError: Python is not installed as a framework
```

=> $ `echo 'backend : TkAgg' >> ~/.matplotlib/matplotlibrc`

