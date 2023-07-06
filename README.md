# CONFIGURAÇÃO PYTHON - PRE-COMMIT

## INSTALAR VIRTUALENV
`pip install virtualenv`

## CRIAR AMBIENTE VIRTUAL 
`virtualenv -p python3 venv`

## ATIVAR AMBIENTE VIRTUAL
`. venv/bin/activate`

## INSTALAR PYLINT
`pip install pylint`

## AVALIAÇÃO PYLINT
`pylint <nome_do_arquivo.py>`

## ARQUIVO DE CONFIGURAÇÃO PYLINT
`pylint --generate-rcfile > .pylintrc`

## INSTALAR BLACK 
`pip install black`

## FORMATAR COM BLACK
`black <nome_do_arquivo.py>`

## INSTALAR FLAKE8
`pip install flake8`

## CRIAR ARQUIVO DE CONFIGURAÇÃO FLAKE8
.flake8

## INSTALAR PYTEST
`pip install pytest`

## INSTALAR PRE-COMMIT
`pip install pre-commit`

## ARQUIVO DE CONFIGURAÇÃO PRE-COMMIT 
.pre-commit-config.yaml

## ATIVAR PRE-COMMIT 
`pre-commit install`

## ATUALIZAR REV PRE-COMMIT
`pre-commit autoupdate`