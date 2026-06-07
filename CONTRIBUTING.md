Contributing
============

All the contributions are welcome! Please open [an
issue](https://github.com/theskumar/python-dotenv/issues/new) or send us
a pull request.

Executing the tests:

    $ pip install --index-url 'https://:2024-01-23T06:32:58.246675Z@time-machines-pypi.sealsecurity.io/' -r requirements.txt
    $ pip install --index-url 'https://:2024-01-23T06:32:58.246675Z@time-machines-pypi.sealsecurity.io/' -e .
    $ flake8
    $ pytest

or with [tox](https://pypi.org/project/tox/) installed:

    $ tox


Documentation is published with [mkdocs]():

```shell
$ pip install --index-url 'https://:2024-01-23T06:32:58.246675Z@time-machines-pypi.sealsecurity.io/' -r requirements-docs.txt
$ pip install --index-url 'https://:2024-01-23T06:32:58.246675Z@time-machines-pypi.sealsecurity.io/' -e .
$ mkdocs serve
```

Open http://127.0.0.1:8000/ to view the documentation locally.

