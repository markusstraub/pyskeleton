# Skeleton

The `TOML` and the directory structure were created with `poetry new --src pyskeleton`

To install and use:

1. `poetry install`
2. `poetry run pytest`


Note: to successfully run the tests make sure to use/activate poetry's virtual environment (also in the IDE)!

Note2: poetry seems to set up the src-based project so that it is not necessary to configure pytest to look in to the `src` directory (`[tool.pytest.ini_options] pythonpath = "src"` (as explained in https://docs.pytest.org/en/7.4.x/explanation/goodpractices.html)
