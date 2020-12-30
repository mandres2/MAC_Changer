# MAC Changer

### Using a Module to Execute System Commands

1. The subprocess module contains a number of functions
2. These functions allow the user to execute system commands
3. Commands depend on the OS which executes the script

* Syntax:

```
import subprocess
subprocess.call("COMMAND", Shell=True)
```
*call() is for an older python version*

*Python 3.5 implemented run()*

```
subprocess.run(args, *, stdin=None, input=None, stdout=None, stderr=None, capture_output=False, shell=False, cwd=None, timeout=None, check=False, encoding=None, errors=None, text=None, env=None, universal_newlines=None, **other_popen_kwargs)
```

Simple Algorithm written in Python 3.0 that verifies the modification of a MAC address.
