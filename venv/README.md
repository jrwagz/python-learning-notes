# Virtual ENV Learning Notes

Create a new virtual environment into the local directory called `env`

```bash
python3 -m venv env
```

activate the virtual environment

```bash
source env/bin/activate
```

Now, once the virtual environment is loaded, all normal python commands, (i.e. python, python3, pip, pip3) will perform their operations within the virtual environment.

dump all dependencies installed in the virtual environment

```bash
pip3 freeze
```

deactivate the virtual environment

```bash
deactivate
```

Further details found [here](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment)