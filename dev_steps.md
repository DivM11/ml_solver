## Adding build and publish 
### Building
```cmd
py -m build
```
or
```sh
python -m build
```

### Get pypi API token
Get an API key from the token from [pypi](https://pypi.org/). It should used in twine upload command below.

### Publish the package to pypi
```cmd
python -m twine upload --repository pypi dist/*
```
or
```sh
py -m twine upload --repository pypi dist/*
```
## Updating release tag to the latest commit
```sh
git tag -f v0.0.1
git push
git push origin -f v0.0.1
```