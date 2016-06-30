##When you find the erro is about the invalid index(maybe did not say so) which ouccer in the parameter of the standard function. May be you need to update your python library

>The code is here:

```python
import pip
from subprocess import call
 
for dist in pip.get_installed_distributions():
    call("pip install --upgrade " + dist.project_name, shell=True)
```
