# Análise descritiva e preditiva de CHURN de cartão de crédito

<a target="_blank" href="https://cookiecutter-data-science.drivendata.org/">
    <img src="https://img.shields.io/badge/CCDS-Project%20template-328F97?logo=cookiecutter" />
</a>


A retenção de clientes é um dos maiores desafios. O ato de cancelar o cartão de crédito é chamado de evento de CHURN.

O objetivo da análise de CHURN presente nesse notebook é:
- Entender o cenário atual da base de associados que utilizam cartão de crédito e entram em CHURN

- Apresentar a primeiros resultados do modelo preditivo para apoiar nas ações de mitigação do CHURN de cartão de crédito

- Apresentar planejamento de próximos passos de ações do time de dados


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
install-jupyter-kernel
```
