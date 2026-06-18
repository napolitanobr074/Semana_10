
# Semana 10 — SQL Avançado e Performance

Esta pasta contém os materiais da **Semana 10** do módulo de Visualização de Dados e Business Intelligence.

O foco desta semana é aprofundar o uso de SQL em cenários de Data Warehouse, trabalhando com consultas mais organizadas, funções analíticas e conceitos de performance.

## Conteúdos trabalhados

Nesta semana, estudamos:

- Subconsultas
- CTEs com `WITH`
- Window Functions
  - `ROW_NUMBER()`
  - `RANK()`
  - `DENSE_RANK()`
  - `SUM() OVER()`
- Conceitos de índices
- Conceitos de particionamento
- Conceitos de Materialized Views
- Boas práticas para consultas analíticas em Data Warehouse

Os exemplos utilizam o modelo de e-commerce trabalhado em aula, com as seguintes tabelas:

- `fato_vendas`
- `dim_cliente`
- `dim_produto`
- `dim_tempo`

---

## Arquivos da pasta

### `Semana_10_Aula.ipynb`

Notebook principal da aula.

Contém os exemplos desenvolvidos em sala, explicações passo a passo e consultas SQL utilizadas para demonstrar os principais conceitos da semana.

Este arquivo deve ser usado para acompanhar as aulas e revisar os exemplos apresentados pela professora.

Conteúdos esperados neste notebook:

- Revisão de consultas SQL em modelo estrela
- Exemplos de subconsultas
- Exemplos de CTEs
- Exemplos de Window Functions
- Demonstrações conceituais de performance
- Observações sobre índices, particionamento e Materialized Views

---

### `Semana_10_Lista_Exercicios_SQL_Avancado_DW_Revisada.ipynb`

Notebook com a lista de exercícios para os alunos.

Contém exercícios progressivos para praticar os conceitos da Semana 10, usando os dados de e-commerce da aula.

Os exercícios foram organizados para praticar:

- Subconsultas
- CTEs
- Window Functions
- Interpretação de consultas analíticas
- Conceitos de performance em Data Warehouse

A Aula 3 foi considerada como uma aula teórica. Por isso, os exercícios práticos focam principalmente nos conteúdos que podem ser executados com segurança no ambiente usado em aula, evitando confundir conceitos específicos de PostgreSQL, DuckDB, particionamento real e Materialized Views.

Este é o arquivo que os alunos devem usar para praticar.

---

### `Semana_10_Gabarito_Exercicios_SQL_Avancado_DW_Revisado.ipynb`

Notebook com o gabarito da lista de exercícios.

Contém as respostas comentadas dos exercícios presentes na lista revisada.

Este arquivo é destinado à professora ou para disponibilização posterior aos alunos, após a realização das atividades.

O gabarito apresenta:

- Consultas SQL resolvidas
- Uso correto dos nomes das tabelas e colunas
- Exemplos com CTEs nomeadas de forma descritiva
- Uso de Window Functions com explicação da lógica
- Ajustes para evitar o uso incorreto de `tempo_sk` como data

---

