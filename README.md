# Python-PostgreSQL
<em>proyecto para practicar conección de Python con PostgreSQL</em>

## Python3 Virtualenv Setup

### Requirements
* Python 3
* Pip 3

#### Instalar [Python3](https://www.python.org/doc/)
```bash
$ brew install python3
```
*pip se instala por defecto con python

#### Actualizar Python:
```bash
$ brew update && brew upgrade python
```

#### Actualizar pip:
```bash
$ python3 -m pip install --upgrade pip
```

#### Instalar [Virtualenv](https://virtualenv.pypa.io/en/stable/):
```bash
$ pip install virtualenv
```

##### Creation of virtualenv:
```bash
$ virtualenv -p python3 <desired-path>
```

##### Activate the virtualenv:
```bash
$ source <desired-path>/bin/activate
```

##### Deactivate the virtualenv:
```bash
$ deactivate
```

##### Ver las libraries instaladas:
```
$ pip list
$ pip freeze
```

##### instalar todas las dependencias requeridas:
```
$ pip install -r ./requirements.txt
```

#### crear el archivo de requerimentos:
```
$ pip freeze > requirements.txt
```

## Instalar [Flask](https://flask.palletsprojects.com/):
```
$ pip install flask
```

## Instalar [Django](https://www.djangoproject.com/):
```
pip install Django==<version>
```


[MacOs Virtualenv](https://sourabhbajaj.com/mac-setup/Python/virtualenv.html)

[Linux Virtualenv](https://www.lunium.com/blog/entornos-virtuales-en-python-3-con-virtualenv-en-linux/#:~:text=Virtualenv%20es%20una%20herramienta%20para,los%20diferentes%20proyectos%20que%20tengamos.)