# my-site

The home page for my site is [https://kenzylouis.github.io/my-site/](https://kenzylouis.github.io/my-site/).

To get started, start a Python virtual environment. You can use one of python's popular tool to manage virtual evnvironent, `pipenv`. <a href="https://pipenv-es.readthedocs.io/es/stable/" target="_blank">Here</a> is the link to the docs.

To Install pipenv with pip:
```shell
pip install pipenv
```

Next initialize the virtual environment:
```shell
pipenv install --python <path to python executable>
```


If you want to Make pipenv create the virtual env in the same folder as your source code:
`export PIPENV_VENV_IN_PROJECT=1`


So, for example on mac, you can initialize a python 3.11 as follow:

```shell
pipenv install --python /Library/Frameworks/Python.framework/Versions/3.11/bin/python3
```

Then, start a virtual environment shell:
```shell
pipenv shell
```

Finally, run your mkdocs server locally for development:
```shell
mkdocs serve
```

Assuming that you already follow the steps to <a href="https://squidfunk.github.io/mkdocs-material/getting-started/" target="_blank">install mkdocs</a> and <a href="https://squidfunk.github.io/mkdocs-material/creating-your-site/" target="_blank">create your site</a>.