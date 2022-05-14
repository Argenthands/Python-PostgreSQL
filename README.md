# Python-PostgreSQL
proyecto para practicar conección de Python con PostgreSQL

## Python3 Virtualenv Setup

##### Requirements
* Python 3
* Pip 3

```bash
$ brew install python3
```

Pip3 is installed with Python3

##### Upgrades

upgrade python:
```bash
$ brew update && brew upgrade python
```

upgrade pip:
```bash
$ python3 -m pip install -upgrade pip
```


##### Installation
To install virtualenv via pip run:
```bash
$ pip install virtualenv
```

##### Usage
Creation of virtualenv:
```bash
$ virtualenv -p python3 <desired-path>
```

Activate the virtualenv:
```bash
$ source <desired-path>/bin/activate
```

Deactivate the virtualenv:
```bash
$ deactivate
```

see the libraries:
```
$ pip list
$ pip freeze
```

[About Virtualenv](https://virtualenv.pypa.io/en/stable/)