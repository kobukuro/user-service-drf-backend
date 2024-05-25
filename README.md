# user-service-drf-backend

## Create the virtual environment using the default Python interpreter

```
poetry env use python
```

## Create the virtual environment using a specific Python interpreter

```
poetry env use "<python-executable-path>"
```

## Activate the virtual environment

```
poetry shell
```

## Exit the virtual environment

```
exit
```

## Install all dependencies in the poetry.lock file

```
poetry install
```

## Show the dependencies listed in the poetry.lock file

```
poetry show
```

## Install dependency

```
poetry add <dependency-name>
```

## Remove dependency

```
poetry remove <dependency-name>
```

## Export the list of dependencies listed in the poetry.lock file to a requirements.txt file

```
poetry export -f requirements.txt -o requirements.txt
```
