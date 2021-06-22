
Back to [Reference Overview](https://github.com/pyrustic/jayson/blob/master/docs/reference/README.md)

# jayson.\_\_init\_\_



<br>


```python

class Error:
    """
    
    """

    def __init__(self, *args, **kwargs):
        """
        
        """

```

<br>

```python

class Jayson:
    """
    Jayson allows you to play with JSON files
    """

    def __init__(self, target, default=None, readonly=False):
        """
        PARAMETERS:
        
        - target: dict or file-like object or a path to a json file. If target is a path
         and this path doesn't exist, a new file will be created or not according
        to the parameter "default
        
        - default: file-like object or a path or a dict.
        
        - readonly: bool
        """

    @property
    def data(self):
        """
        The dict-like representation of the JSON file
        """

    @data.setter
    def data(self, val):
        """
        The dict to push into JSON file
        """

    @property
    def default(self):
        """
        
        """

    @property
    def target(self):
        """
        
        """

    def reload(self):
        """
        Reload data from JSON file
        """

    def save(self):
        """
        "
        Push data into the JSON file (not the default file !) if 'readonly' is False
        """

```

