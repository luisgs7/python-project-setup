### Configurações Recomendadas para um Projeto Python
#
01 - Inicializar repositório git

02 - Criar o arquivo .gitignore

03 - Criar o ambiente virtual

04 - Instalar o pylint

 - pip3 install pylint
 - ctrl + shift + p -> select Linter -> pylint
 - pylint --generate-rcfile > .pylintrc
 - pylint <file.py>

05 - Adicionar Dependencias ao requirements.txt 
 - pip freeze > requirements.txt

06 - Instalar o black (Formatar código de acordo com o pep8)
 - pip3 install black

07 - Instalar o flake8
 - pip3 install flake8

08 - Criar o arquivo .flake8
 - Adicionar configurações

09 - Instalar o módulo de testes pytest
 - pip3 install pytest
 - pytest -v

10 - Instalar o pre-commit
 - pip install pre-commit
 - pre-commit install 
 - criar o arquivo .pre-commit-config.yaml
 - adicionar as configurações no arquivo

11 - Ao clonar este repositório basta criar o ambiente virtual, e em seguida executar o comando abaixo, na pasta do projeto.

 - venv/bin/pip3 install -r requirements.txt