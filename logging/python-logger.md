# Python logger

## Registering logger

```python
def __init__(self):
    super(Class, self).__init__()
    self._logger = logging.getLogger("DiceNotationListener")
```

## Logging

```python
self._logger.debug("Showing %s on log", data)
```

