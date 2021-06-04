###### pipenv commands
|                      |                          |
| ---------------------|:------------------------:|
| pipenv --rm          | remove env               |
| pipenv install --dev | install dev dependencies |
| pipenv shell         | run shell                |
| pipenv --venv        | check path env           |

---

###### coverage commands
|                                                 |                                 |
| ------------------------------------------------|:-------------------------------:|
| coverage run --omit='*/{venv}/*' manage.py test |                                 |
| coverage run manage.py test                     | run tests                       |
| coverage report                                 | coverage information            |