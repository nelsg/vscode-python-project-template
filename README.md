# Instructions

* Créer le virtualenv : `virtualenv -p python3 .venv`
* Charger le virtuelenv : `source .venv/bin/activate`
* Installer les requirements : `pip install -r requirements.txt`
* Installer les requirements des tests : `pip install -r tests/requirements.txt`
* Exécuter les TU : `python3 -m pytest tests -v`
* Exécuter la couverture : `python3 -m pytest --cov-report xml:cov.xml --cov my_module tests -v`

# Choix du template

* Formatage python : **yapf**. Autre : https://code.visualstudio.com/docs/python/editing#_formatting
* Analyse de code : **pylint**. Autre : https://code.visualstudio.com/docs/python/linting
* Tests unitaires : **pytest**. Autre : https://code.visualstudio.com/docs/python/unit-testing

* Toutes les options pour python : https://code.visualstudio.com/docs/python/settings-reference