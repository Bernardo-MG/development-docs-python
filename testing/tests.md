# Tests

Just like when building the setup.py file can be used for running the tests:

```text
$ python setup.py test
```

This allows the project to select which testing framework or configuration it will use.

## Test profiles

If using test profiles, it is possible to run just one of them:

```text
$ python setup.py test -p "py36"
```

