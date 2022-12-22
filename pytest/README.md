# pytest learning notes

Execute all tests in the current directory and recursively

```bash
pytest
```

Just run tests on particular subfolder(s) or file(s)

```bash
pytest <subfolder_name> <file_name> <subfolder_name_2> ...
```

- [pytest standard test discovery rules](https://docs.pytest.org/en/7.2.x/explanation/goodpractices.html#test-discovery)

## Organization best practice

```bash
pyproject.toml
src/
    mypkg/
        __init__.py
        app.py
        view.py
tests/
    test_app.py
    test_view.py
    ...
```
