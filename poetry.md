```


pip install poetry
poetry init
poetry install
poetry env info -p
poetry config virtualenvs.in-project true
poetry shell
poetry add requests
poetry remove requests
exit
poetry env list
deactivate
poetry config repositories.test-pypi https://test.pypi.org/legacy/
poetry config pypi-token.test-pypi <token>
poetry build
poetry publish -r test-pypi
poetry config virtualenvs.create false
```

https://www.youtube.com/watch?v=0f3moPe_bhk&t=409s
