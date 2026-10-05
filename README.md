# 📊 Análise de Dados com Python e Pandas

Projeto prático desenvolvido para o desafio final do curso **Análise de dados com Python e Pandas** da DIO.

## 🎯 Objetivo

Aplicar os conceitos estudados durante o curso em um conjunto de dados de vendas, utilizando Python, Pandas e Matplotlib.

O projeto trabalha com:

- leitura de arquivo Excel;
- exploração de DataFrames;
- tipos de dados;
- valores ausentes e duplicados;
- criação de novas colunas;
- operações matemáticas;
- agrupamentos com `groupby`;
- ordenação;
- trabalho com datas;
- análise de receita, custo e lucro;
- análise de produtos, marcas e lojas;
- visualização de dados.

## 🛠️ Tecnologias

- Python
- Pandas
- Matplotlib
- Jupyter Notebook / Google Colab
- Excel
- Git e GitHub

## 📁 Estrutura

```text
projeto-analise-dados-python-pandas/
│
├── analise_adventureworks.ipynb
├── dados_tratados.csv
├── requirements.txt
│
├── datasets/
│   └── AdventureWorks.xlsx
│
└── graficos/
    ├── lucro_por_ano.png
    ├── produtos_mais_vendidos.png
    ├── lucro_por_marca.png
    ├── receita_por_mes.png
    └── tempo_de_envio.png
```

## 📊 Dataset

O arquivo utilizado possui **904 registros e 16 colunas**, contendo informações como data de venda, data de envio, loja, produto, cliente, custo, preço, quantidade, desconto, valor da venda, fabricante, marca, classe e cor.

## 🔎 Principais resultados

| Indicador | Resultado |
|---|---:|
| Registros | 904 |
| Colunas | 16 |
| Receita total | R$ 5,984,606.14 |
| Custo total | R$ 2,486,783.05 |
| Lucro total | R$ 3,497,823.09 |
| Margem de lucro | 58.45% |
| Tempo médio de envio | 8.54 dias |
| Período | 02/01/2008 a 31/12/2009 |

## 💡 Insights

### Desempenho anual

Em 2008, a receita foi de **R$ 3,187,607.65**, enquanto em 2009 foi de **R$ 2,796,998.49**.

Apesar da quantidade de produtos vendidos ter aumentado em 2009, a receita e o lucro foram menores, indicando uma mudança no perfil dos produtos comercializados.

### Marcas

A marca com maior lucro total foi **Fabrikam**, com aproximadamente **R$ 2,591,111.90** de lucro.

### Produtos

O produto com maior quantidade vendida foi:

**Headphone Adapter for Contoso Phone E130 Silver**

com **25,232 unidades**.

### Logística

O tempo médio de envio foi de **8.54 dias**, com mínimo de 4 dias e máximo de 20 dias.

## ▶️ Como executar

### Google Colab

Faça upload do arquivo `AdventureWorks.xlsx` e abra o notebook:

`analise_adventureworks.ipynb`

### Localmente

Instale as dependências:

```bash
pip install -r requirements.txt
```

Depois abra o notebook:

```bash
jupyter notebook analise_adventureworks.ipynb
```

## 🎓 Sobre o projeto

Este projeto foi desenvolvido como aplicação prática dos conteúdos estudados no curso de análise de dados com Python e Pandas.

## 👨‍💻 Autor

**Gabriel de Souza Oliveira**

Projeto desenvolvido para composição de portfólio no GitHub.
