# Behave-python-base
Estrutura Base para automação Python com Selenium e Behave

Behave é um framework que permite a escrita de testes automatizados em Gherkin no Python. Utilizaremos ele juntamente com o Selenium para estruturar nosso projeto.

Estrutura de Diretórios:

Features: armazena os arquivos .feature utilizados para a escrita dos testes em Gherkin ou BDD.

Pages: armazena os arquivos que contêm os seletores e os comandos executados em cada página.

Steps: armazena os arquivos com os steps do Gherkin. Responsável por conectar os steps escritos em Gherkin com o código das pages.

Browser.py: arquivo de configurações relacionadas ao browser.

Environment.py: arquivo de configurações relacionadas à execução dos testes.

Pré-requisitos:
pip install selenium
pip install webdriver-manager

Instalar Python 3.5+
Instalar alguma IDE ou editor de texto para desenvolvimento como PyCharm
Instalar dependências executando na raiz do projeto: pip install -r requirements.txt
Tutorial completo: acesse aqui

Execução dos testes:
Pelo terminal, executar na raiz do projeto o comando: behave
