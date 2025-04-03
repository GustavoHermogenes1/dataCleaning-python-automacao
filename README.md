# dataCleaning-python-automacao
Automatização do tratamento de dados para o dashboard de Compras, identificada durante um processo interno da empresa. O projeto utiliza Python e a biblioteca Pandas para otimizar a manipulação de dados, garantindo mais eficiência e precisão na geração de insights para a equipe de Compras.

A automatização foi feita de forma real com muitos outros dados que não poderiam ser colocados nesse projeto por conta de regras internas da empresa. Portanto, para respeitar essas regras e apenas seguir com a demonstração dessa prática, eu decidi criar arquivos cópias que não contém nenhum tipo de dado sensível ou informações de funcionários, fornedores e/ou clientes.

# Descrição do Problema
No processo de atualização do dashboard de compras, era necessário extrair dados do SAP, tratá-los manualmente no Excel e preencher templates padronizados definidos pelo time de compras. Esse fluxo, além de ser trabalhoso e consumir muito tempo, aumentava significativamente as chances de erro humano no preenchimento dos templates.

Diante desse cenário, identificamos uma oportunidade de automação para tornar o processo mais eficiente e confiável. Com a aplicação de técnicas de automação e ciência de dados, conseguimos otimizar essa rotina, reduzindo o esforço manual e gerando relatórios automaticamente, garantindo maior precisão e agilidade.

# Ferramentas usadas
# - Python:
Linguagem de programação muito utilizada para automação de tarefas, análise, tratamento e manipulação de dados e arquivos.
# - Pandas:
A biblioteca Pandas é uma ferramenta de análise de dados em Python, que permite manipular e analisar dados estruturados. É uma biblioteca de código aberto, que pode ser usada para trabalhar com dados tabulares, como planilhas e bancos de dados. Para utilizá-la é necessário fazer a instalação no código .py, para isso utiliza-se o comando 'pip install' pandas. Além disso, o comando 'import pandas' é importante para importar a biblioteca e suas funcionalidades para o código em Pyhton.

# Estrutura do projeto
- automacao_processos.py: Esse é o aquivo que contém o código em Python da automação do processo.
- Payment List: Arquivo extraído do SAP, será manipulado e usado para preencher o template que é considerado base de dados para o dashboard de compras.
- PO List: Arquivo extraído do SAP, será manipulado e usado para preencher o template que é considerado base de dados para o dashboard de compras.
- Spend List: Arquivo extraído do SAP, será manipulado e usado para preencher o template que é considerado base de dados para o dashboard de compras.
- Template Payment: Arquivo pré-definido pela equipe de compras que será preenchido com as informações de Payment List.
- Template PO: Arquivo pré-definido pela equipe de compras que será preenchido com as informações de PO List.
- Template Spend: Arquivo pré-definido pela equipe de compras que será preenchido com as informações de Spend List.
- 3. Template for Manual Data - Payments Details PBI: Arquivo resultado (já preenchido com os dados corretos) e que será utilizado como base de dados do dashboard de compras.
- 2. Template for Manual Data - PO Details PBI: Arquivo resultado (já preenchido com os dados corretos) e que será utilizado como base de dados do dashboard de compras.
- 1. Template for Manual Data - Spend Details PBI: Arquivo resultado (já preenchido com os dados corretos) e que será utilizado como base de dados do dashboard de compras.
