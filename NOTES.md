## Create pypi package and upload it

```
python setup.py sdist
twine upload --skip-existing dist/*
```
