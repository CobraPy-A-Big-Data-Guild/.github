# Seja bem-vindo(a) ao workspace de desenvolvimento colaborativo da CobraPy
Repositório para os produtos e projetos analíticos da Livar.

Como o repositório é organizado:

-> Projects (pasta dedicada a projetos)

Sub-pastas de projeto:
 - src: pasta com o código fonte do projeto
 - tests: pasta dedicada a testes unitários

Sub-pastas do source (src):
- models (pasta dedicada a modelos do projeto)
- etls (pasta dedicada a etls projeto)
- data-providers (pasta dedicada aos provedores de dados do projeto)
- dashboards (pasta dedicada a dashboards projeto)
- adhoc-analysis (pasta dedicada a análises adhoc do projeto)
- utils (pasta dedicada a utilitários, por exemplo, classe para leitura e gravação de dados)

**Não adicionar pastas vazias ao projeto, só crie uma sub-pasta se ela for utilizada**

-> Utils (pasta dedicada a funções que podem ser reutilizadas entre os projetos)

Exemplo visual da organização do diretório:

```
├── projects
│   ├──project1 (nome do projeto)
│   ├── ├── src
│   ├── ├── ├── models
│   ├── ├── ├── etls
│   ├── ├── ├── data_providers
│   ├── ├── ├── dashboards
│   ├── ├── ├── adhoc_analysis
│   ├── ├── tests
│   ├──project2
│   ├── ├── src
│   ├── ├── ├── models
│   ├── ├── ├── etls
│   ├── ├── ├── data_providers
│   ├── ├── ├── dashboards
│   ├── ├── ├── adhoc_analysis
│   ├── ├── tests
.
.
.
├── utils
```

Códigos devem ser escritos em inglês e o nome das pastas do diretório também!

A linguagem principal utilizada é o Pyspark.
