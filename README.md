# test-poetry-plugins
A small project to test the poetry application plugins

This project does not works. I have:
- created the project using `poetry init`
- created a plugins.py file according to the documentation
- added an entry in the `pyproject.toml` file
- run `poetry install`

But none of theses commands works:
- `poetry list`: does not contains my-command
- `poetry self show plugins`: does not list my plugin
- `poetry my-command`
