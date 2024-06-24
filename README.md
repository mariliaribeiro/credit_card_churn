# Análise descritiva e preditiva de CHURN de cartão de crédito

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>


A retenção de clientes é um dos maiores desafios. O ato de cancelar o cartão de crédito é chamado de evento de CHURN.

O objetivo da análise de CHURN presente nesse notebook é:
- Entender o cenário atual da base de associados que utilizam cartão de crédito e entram em CHURN

- Apresentar a primeiros resultados do modelo preditivo para apoiar nas ações de mitigação do CHURN de cartão de crédito

- Apresentar planejamento de próximos passos de ações do time de dados

Você irá encontrar a análise de CHURN no arquivo `churn.ipynb` presente na raiz do repositório.

A base de dados utilizada para a análise é composta pelos três arquivos descritos abaixo:

- `CBO2002 - Ocupacao.csv`: contém dados da [Classificação Brasileira de Opucpações (CBO)](https://empregabrasil.mte.gov.br/76/cbo/) que retrata a realidade das profissões do mercado de trabalho brasileiro com base na Portaria nº 397, de 10.10.2002. O CBO reconhece a existência da profissão mas na sua regulamentação.
- `cnae.xlsx`: contém dados da [Classificação Nacional de Atividades Econômicas (CNAE)](https://www.gov.br/receitafederal/pt-br/assuntos/orientacao-tributaria/cadastros/cnpj/classificacao-nacional-de-atividades-economicas-2013-cnae) que padroniza o código de atividades econicas.
- `case_mep_dados.xls`: a planilha contém várias abas que representam bases de dados como: cadastro de clientes e informações complementares, transações financeiras realizadas com o cartão de crédito, abertura de chamados e clientes que deram CHURN.


## Primeiros passos

Pré requisitos:
- Python 3.10 a 3.13
- Virtualenv

Para executar o projeto em sua máquina é necessário realizar os seguintes passos:

- Criar uma virtualenv
```
python -m venv venv
``` 

- Ativiar a virtualenv
```
source venv/bin/activate
```

- Instalar o poetry que é o gerenciador de pacotes de dependências do projeto
```
pip install poetry
```

- Instalar as dependências do projeto com o poetry
```
poetry update
```

Se você estiver utilizando o VSCode, assim como eu, será necessário instalar a extensão do jupyter. E depois rodar o comando abaixo presente no arquivo Makefile, para poder relacionar o virtualenv com o kernel do jupter notebook.
```
make install-jupyter-kernel
```
