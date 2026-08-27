# 🛍️ Alura Store — Análise de Desempenho das Lojas

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Folium](https://img.shields.io/badge/Folium-Geospatial%20Analysis-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)

> **3ª Fase — 1º Desafio do Challenge Alura Store**

## 📊 Sobre o Projeto

O projeto **Alura Store** foi desenvolvido como parte do desafio de Data Science da Alura e tem como objetivo analisar o desempenho de quatro lojas da rede fictícia **Alura Store**.

A proposta é utilizar dados de vendas para auxiliar o **Senhor João** na identificação da loja que apresenta o menor desempenho, considerando diferentes indicadores de negócio.

A análise combina **tratamento de dados, análise exploratória, estatística descritiva e visualização de dados** para transformar os registros de vendas em informações úteis para tomada de decisão.

---

## 🎯 Objetivo

Identificar qual das quatro lojas apresenta o menor desempenho geral a partir da análise de:

* 💰 Faturamento total;
* 🛒 Vendas por categoria;
* ⭐ Avaliação média dos clientes;
* 📦 Produtos mais e menos vendidos;
* 🚚 Frete médio;
* 🌎 Distribuição geográfica das vendas.

---

## 🗂️ Dados analisados

Os dados utilizados possuem informações relacionadas a:

* Produto;
* Categoria do produto;
* Preço;
* Frete;
* Data da compra;
* Vendedor;
* Local da compra;
* Avaliação da compra;
* Tipo de pagamento;
* Quantidade de parcelas;
* Latitude;
* Longitude.

O notebook realiza a importação dos dados das quatro lojas e posteriormente consolida as informações para permitir análises comparativas.

---

## 🔎 Análises realizadas

### 1. 💰 Faturamento por Loja

Os dados das quatro lojas foram consolidados e agrupados para calcular o faturamento total de cada unidade.

| Loja       |         Faturamento |
| ---------- | ------------------: |
| 🥇 Loja 1  | **R$ 1.534.509,12** |
| 🥈 Loja 2  | **R$ 1.488.459,06** |
| 🥉 Loja 3  | **R$ 1.464.025,03** |
| 4️⃣ Loja 4 | **R$ 1.384.497,58** |

A **Loja 1** apresentou o maior faturamento, enquanto a **Loja 4** apresentou o menor.

Para facilitar a interpretação, foi desenvolvido um **gráfico de pizza**, apresentando a participação de cada loja no faturamento total, com porcentagens e valores em reais.

---

### 2. 🛒 Vendas por Categoria

Foi realizada uma análise da quantidade de produtos vendidos em cada categoria para as quatro lojas.

Entre as categorias analisadas estão:

* Móveis;
* Eletrônicos;
* Brinquedos;
* Eletrodomésticos;
* Esporte e lazer;
* Instrumentos musicais;
* Livros;
* Utilidades domésticas.

Na **Loja 1**, por exemplo, as categorias com maior quantidade de vendas foram **móveis (465)** e **eletrônicos (448)**.

Essa análise permite identificar quais categorias possuem maior demanda e podem receber maior atenção em estratégias comerciais e de estoque.

---

### 3. ⭐ Média de Avaliação dos Clientes

A satisfação dos clientes foi analisada utilizando a média da coluna **"Avaliação da compra"** para cada loja.

| Loja       | Avaliação Média |
| ---------- | --------------: |
| 🥇 Loja 3  |        **4,05** |
| 🥈 Loja 2  |        **4,04** |
| 🥉 Loja 4  |        **4,00** |
| 4️⃣ Loja 1 |        **3,98** |

A **Loja 3** apresentou a melhor avaliação média, enquanto a **Loja 1** apresentou a menor média entre as quatro lojas.

Foi desenvolvido um gráfico combinando **colunas e linha de tendência**, permitindo comparar visualmente o desempenho das unidades.

---

### 4. 📦 Produtos Mais e Menos Vendidos

Foi criada uma tabela comparativa identificando o produto com maior e menor quantidade de vendas em cada loja.

| Loja   | Produto mais vendido     | Qtd. | Produto menos vendido | Qtd. |
| ------ | ------------------------ | ---: | --------------------- | ---: |
| Loja 1 | Micro-ondas              |   60 | Headset               |   33 |
| Loja 2 | Iniciando em programação |   65 | Jogo de tabuleiro     |   32 |
| Loja 3 | Kit banquetas            |   57 | Blocos de montar      |   35 |
| Loja 4 | Cama box                 |   62 | Guitarra              |   33 |

Os resultados foram obtidos a partir da contagem de ocorrências de cada produto por loja.
Essa análise permite identificar produtos com maior aceitação e aqueles que podem demandar revisão de estratégia comercial.

---

### 5. 🚚 Frete Médio por Loja

O custo médio de frete foi calculado para cada unidade.

| Loja   |  Frete Médio |
| ------ | -----------: |
| Loja 1 | **R$ 34,69** |
| Loja 2 | **R$ 33,62** |
| Loja 3 | **R$ 33,07** |
| Loja 4 | **R$ 31,28** |

A **Loja 1** apresentou o maior custo médio de frete, enquanto a **Loja 4** apresentou o menor.

Esse indicador é relevante para uma eventual análise de eficiência logística e custos operacionais.

---

### 6. 🌎 Análise Geográfica

Como análise adicional, foi realizada uma visualização da distribuição geográfica das vendas utilizando as coordenadas de **latitude e longitude** disponíveis nos dados.

O gráfico de dispersão permite observar a distribuição das vendas por loja e identificar visualmente diferentes regiões de concentração.

---

## 📈 Visualizações

O projeto apresenta diferentes visualizações para facilitar a interpretação dos resultados:

* 🥧 Gráfico de pizza — faturamento por loja;
* 📊 Gráfico de colunas — média de avaliação;
* 📈 Linha de tendência — avaliação das lojas;
* 🚚 Gráfico de linha — frete médio;
* 🌎 Scatter plot — distribuição geográfica das vendas;
* 📋 Tabelas comparativas — produtos e indicadores.

---

## 🛠️ Tecnologias utilizadas

### Linguagem

* **Python 3.x**

### Bibliotecas

* **Pandas** — manipulação, transformação e análise dos dados;
* **Matplotlib** — criação das visualizações;
* **Folium** — análise e visualização geográfica;
* **Jupyter Notebook** — desenvolvimento e documentação da análise;
* **Google Colab** — execução e compartilhamento do notebook.

---

## 📁 Estrutura do Projeto

```text
3-fase---1-Desafio-do-Challenge-Alura-Store/
│
├── AluraStoreBrasil.ipynb
├── README.md
│
└── [arquivos de apoio]
```

O principal artefato do projeto é o notebook `AluraStoreBrasil.ipynb`, que contém a importação dos dados, tratamento, análises, tabelas, gráficos e conclusão.

---

## ▶️ Como executar

### Google Colab

O notebook pode ser executado diretamente no Google Colab.

[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Lufsenna/3-fase---1-Desafio-do-Challenge-Alura-Store/blob/main/AluraStoreBrasil.ipynb)

### Execução local

Clone o repositório:

```bash
git clone https://github.com/Lufsenna/3-fase---1-Desafio-do-Challenge-Alura-Store.git
```

Entre na pasta:

```bash
cd 3-fase---1-Desafio-do-Challenge-Alura-Store
```

Instale as dependências:

```bash
pip install pandas matplotlib folium jupyter
```

Execute o notebook:

```bash
jupyter notebook AluraStoreBrasil.ipynb
```

---

## 💡 Principais Insights

A análise dos indicadores apresenta alguns pontos importantes:

### 🏆 Loja 1

* Maior faturamento: **R$ 1.534.509,12**;
* Menor avaliação média: **3,98**;
* Maior frete médio: **R$ 34,69**.

Apesar de apresentar o maior faturamento, a Loja 1 possui indicadores que podem ser melhorados, especialmente em relação à satisfação dos clientes e aos custos de frete.

### ⭐ Loja 3

* Melhor avaliação média: **4,05**;
* Faturamento de **R$ 1.464.025,03**;
* Frete médio de **R$ 33,07**.

A Loja 3 apresenta o melhor resultado de satisfação entre as quatro unidades.

### ⚠️ Loja 4

* Menor faturamento: **R$ 1.384.497,58**;
* Avaliação média: **4,00**;
* Menor frete médio: **R$ 31,28**.

## A Loja 4 apresenta o menor faturamento, embora também possua o menor custo médio de frete.

## 🎯 Conclusão e Recomendação

Com base nos indicadores analisados, a **Loja 4 apresenta o menor faturamento entre as quatro unidades**, sendo o principal ponto de atenção para a decisão do Senhor João.

Entretanto, a decisão não deve considerar apenas o faturamento. A Loja 4 apresenta **frete médio inferior às demais lojas** e uma avaliação média de **4,00**, portanto é importante analisar conjuntamente os diferentes indicadores antes de uma decisão definitiva.

A análise também evidencia oportunidades de melhoria na **Loja 1**, principalmente em relação à satisfação dos clientes e aos custos logísticos.

Dessa forma, os dados podem apoiar o Senhor João em uma decisão mais estratégica, baseada não apenas em vendas, mas também em **experiência do cliente, produtos, logística e distribuição geográfica**.

---

## 📚 Aprendizados

Este projeto possibilitou praticar conceitos importantes de **Data Science e Análise de Dados**, incluindo:

* Importação e leitura de arquivos CSV;
* Tratamento e organização de dados;
* `DataFrame` e operações com Pandas;
* Agrupamento e agregação de dados;
* Cálculo de médias e totais;
* Análise comparativa;
* Criação de visualizações;
* Análise geográfica;
* Transformação de dados em insights para negócio;
* Comunicação de resultados por meio de storytelling com dados.

---

## 👨‍💻 Autor

**Luciano Sena**

Projeto desenvolvido como parte da formação em **Data Science — Oracle Next Education (ONE) / Alura**.

🔗 **GitHub:** [Lufsenna](https://github.com/Lufsenna)

---

⭐ Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório!
