# user-service-drf-backend

## Create the virtual environment using the default Python interpreter

```sh
poetry env use python
```

## Create the virtual environment using a specific Python interpreter

```sh
poetry env use "<python-executable-path>"
```

## Activate the virtual environment

```sh
poetry shell
```

## Exit the virtual environment

```sh
exit
```

## Install all dependencies in the poetry.lock file

```sh
poetry install
```

## Show the dependencies listed in the poetry.lock file

```sh
poetry show
```

## Install dependency

```sh
poetry add <dependency-name>
```

## Remove dependency

```sh
poetry remove <dependency-name>
```

## Export the list of dependencies listed in the poetry.lock file to a requirements.txt file

```sh
poetry export -f requirements.txt -o requirements.txt
```
