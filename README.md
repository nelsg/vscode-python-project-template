# VSCode Python Project Template

Template for my python (version 3) projects with vscode

## Commands

* Create virtualenv virtualenv : `virtualenv -p python3 .venv`
* Load/Source virtuelenv : `source .venv/bin/activate`
* Install requirements : `pip install -r requirements.txt`
* Install test requirements : `pip install -r tests/requirements.txt`
* Launch unitary tests : `python3 -m pytest tests -v`
* Launch coverage tests : `python3 -m pytest --cov-report xml:cov.xml --cov my_module tests -v`

## Tools choices

* Format python code with **autopep8**. Others here : https://code.visualstudio.com/docs/python/editing#_formatting
* Static analysis with **pylint**. Others here : https://code.visualstudio.com/docs/python/linting
* Unitary tests with **pytest**. Others here : https://code.visualstudio.com/docs/python/unit-testing

* Available options for python with vscode available here : https://code.visualstudio.com/docs/python/settings-reference

## Extensions

Usefull extensions :

* Python (https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* Coverage Gutters (https://marketplace.visualstudio.com/items?itemName=ryanluker.vscode-coverage-gutters)
* Better Comments (https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

## Tasks

* Unitary tests with code coverage

## Use it

* Clone this repo as a new vscode workspace
* Create virtualenv and install requirements (see [Commands](Commands))
* Rename folder *my_module* with your module name
* In *.vscode/tasks.json*, replace *my_module* by your module name
* Fix module import in *main.py* and *./tests/test_my_module.yy* if needed
* Try everything by:
    * Launching unitary tests
    * Launching task
    * Launching configurations
    * Debugging with a breakpoint

## Sources

* https://github.com/dwd-umd/python-project-template