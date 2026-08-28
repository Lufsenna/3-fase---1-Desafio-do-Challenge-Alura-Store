# 🛍️ Alura Store — Análise de Desempenho das Lojas

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)](https://matplotlib.org/)
[![Folium](https://img.shields.io/badge/Folium-Geospatial%20Analysis-green)](https://python-visualization.github.io/folium/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow?logo=googlecolab)](https://colab.research.google.com/)

> **3ª Fase — 1º Desafio | Data Science — Alura / Oracle Next Education (ONE)**

---

## 📌 Sobre o projeto

O **Alura Store** é um projeto de análise de dados desenvolvido como parte da formação em **Data Science da Alura / Oracle Next Education (ONE)**.

O desafio consiste em analisar os dados de vendas de quatro lojas fictícias da rede **Alura Store**, com o objetivo de auxiliar o **Senhor João** a identificar qual unidade apresenta o menor desempenho geral e, consequentemente, pode ser considerada para encerramento.

A análise combina **tratamento de dados, análise exploratória, estatística descritiva, visualização de dados e interpretação de indicadores de negócio**.

O objetivo não é analisar apenas o faturamento, mas considerar diferentes indicadores para obter uma visão mais completa do desempenho de cada loja.

---

# 🎯 Objetivo

Identificar a loja com menor desempenho entre as quatro unidades analisadas, considerando os seguintes indicadores:

* 💰 Faturamento total;
* 🛒 Quantidade de vendas por categoria;
* ⭐ Avaliação média dos clientes;
* 📦 Produtos mais e menos vendidos;
* 🚚 Frete médio;
* 🌎 Distribuição geográfica das vendas.

A partir desses indicadores, foram desenvolvidos **insights e recomendações de negócio** para apoiar a tomada de decisão.

---

# 📊 Perguntas de negócio

A análise busca responder principalmente às seguintes perguntas:

1. Qual loja apresenta o maior faturamento?
2. Qual loja apresenta o menor faturamento?
3. Quais categorias possuem maior volume de vendas?
4. Qual loja possui a melhor avaliação média?
5. Qual loja possui a pior avaliação média?
6. Quais são os produtos mais vendidos?
7. Quais são os produtos menos vendidos?
8. Qual loja apresenta o maior custo médio de frete?
9. Qual loja apresenta o menor custo médio de frete?
10. Existe algum padrão geográfico na distribuição das vendas?
11. Qual loja apresenta o menor desempenho geral?

---

# 🗂️ Dados analisados

Os dados utilizados contêm informações relacionadas às vendas realizadas pelas quatro lojas.

Entre as principais informações estão:

* Produto;
* Categoria;
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

Os dados foram organizados e consolidados para permitir uma comparação entre as quatro lojas.

---

# 🔎 Análises realizadas

## 1. 💰 Faturamento por loja

O faturamento total foi calculado a partir do valor dos produtos vendidos em cada loja.

### Resultado

| Loja       |         Faturamento |
| ---------- | ------------------: |
| 🥇 Loja 1  | **R$ 1.534.509,12** |
| 🥈 Loja 2  | **R$ 1.488.459,06** |
| 🥉 Loja 3  | **R$ 1.464.025,03** |
| 4️⃣ Loja 4 | **R$ 1.384.497,58** |

### Insight

A **Loja 1** apresentou o maior faturamento, enquanto a **Loja 4** apresentou o menor.

A diferença entre a Loja 1 e a Loja 4 é de aproximadamente **R$ 150 mil**.

Esse indicador representa um dos principais pontos utilizados na avaliação do desempenho das unidades.

---

## 2. 🛒 Vendas por categoria

Foi analisada a quantidade de produtos vendidos em cada categoria para identificar quais segmentos apresentam maior demanda.

Entre as categorias analisadas estão:

* Móveis;
* Eletrônicos;
* Brinquedos;
* Eletrodomésticos;
* Esporte e lazer;
* Instrumentos musicais;
* Livros;
* Utilidades domésticas.

A análise permite identificar categorias com maior volume de vendas e possíveis oportunidades de estoque e estratégia comercial.

### Exemplo — Loja 1

Na Loja 1, algumas das categorias com maior quantidade de vendas foram:

* **Móveis: 465 vendas**
* **Eletrônicos: 448 vendas**

Esse tipo de análise permite identificar quais segmentos apresentam maior participação no volume comercial da unidade.

---

# ⭐ 3. Média de avaliação dos clientes

A satisfação dos clientes foi analisada utilizando a média da coluna **"Avaliação da compra"** para cada loja.

### Resultado

| Loja       | Avaliação média |
| ---------- | --------------: |
| 🥇 Loja 3  |        **4,05** |
| 🥈 Loja 2  |        **4,04** |
| 🥉 Loja 4  |        **4,00** |
| 4️⃣ Loja 1 |        **3,98** |

### Insight

A **Loja 3** apresentou a melhor avaliação média, enquanto a **Loja 1** apresentou a menor avaliação entre as quatro lojas.

Isso demonstra que o maior faturamento da Loja 1 não significa necessariamente maior satisfação dos clientes.

---

# 📦 4. Produtos mais e menos vendidos

Foi realizada uma análise para identificar os produtos com maior e menor quantidade de vendas em cada loja.

### Resultado

| Loja   | Produto mais vendido     | Vendas | Produto menos vendido | Vendas |
| ------ | ------------------------ | -----: | --------------------- | -----: |
| Loja 1 | Micro-ondas              |     60 | Fone de ouvido        |     33 |
| Loja 2 | Iniciando em programação |     65 | Jogo de tabuleiro     |     32 |
| Loja 3 | Kit banquetas            |     57 | Blocos de montar      |     35 |
| Loja 4 | Caixa Cama               |     62 | Guitarra              |     33 |

### Insight

A análise dos produtos permite identificar:

* produtos com maior demanda;
* produtos com menor saída;
* possíveis oportunidades de estoque;
* possíveis oportunidades de campanhas promocionais;
* produtos que podem exigir revisão de estratégia comercial.

---

# 🚚 5. Frete médio por loja

O custo médio de frete foi calculado para cada unidade.

### Resultado

| Loja   |  Frete médio |
| ------ | -----------: |
| Loja 1 | **R$ 34,69** |
| Loja 2 | **R$ 33,62** |
| Loja 3 | **R$ 33,07** |
| Loja 4 | **R$ 31,28** |

### Insight

A **Loja 1** apresentou o maior frete médio, enquanto a **Loja 4** apresentou o menor.

Esse indicador é relevante para uma análise de eficiência logística e custos operacionais.

---

# 🌎 6. Análise geográfica

Como análise complementar, foi utilizada a latitude e longitude disponíveis no dataset para visualizar a distribuição geográfica das vendas.

A análise permite observar:

* concentração das vendas;
* distribuição espacial dos clientes;
* possíveis diferenças regionais;
* comportamento geográfico das unidades.

Para essa etapa foi utilizada a biblioteca **Folium**.

---

# 📈 Visualizações

Foram desenvolvidas diferentes visualizações para facilitar a interpretação dos resultados.

### Principais visualizações

* 🥧 Gráfico de pizza — participação no faturamento;
* 📊 Gráfico de barras — comparação entre lojas;
* 📈 Gráfico de linha — comparação de indicadores;
* 📦 Gráficos relacionados a produtos;
* 🚚 Comparação do frete médio;
* 🌎 Visualização geográfica;
* 📋 Tabelas comparativas.

As visualizações foram utilizadas como apoio à análise e ao storytelling dos dados.

---

# 🛠️ Tecnologias utilizadas

## Linguagem

* **Python 3.x**

## Bibliotecas

* **Pandas** — manipulação e análise de dados;
* **NumPy** — operações numéricas;
* **Matplotlib** — visualização de dados;
* **Folium** — visualização geográfica;
* **Jupyter Notebook** — desenvolvimento e documentação;
* **Google Colab** — execução e compartilhamento do notebook.

## Ferramentas

* Git;
* GitHub;
* Google Colab;
* Jupyter Notebook.

---

# 📁 Estrutura do projeto

```text
3-fase---1-Desafio-do-Challenge-Alura-Store/
│
├── README.md
│
├── AluraStoreBrasil.ipynb
│
└── arquivos de apoio/
```

### Principais arquivos

| Arquivo                  | Descrição                                            |
| ------------------------ | ---------------------------------------------------- |
| `README.md`              | Documentação do projeto                              |
| `AluraStoreBrasil.ipynb` | Notebook com análise, códigos, gráficos e resultados |

> O código completo da análise está documentado no notebook `AluraStoreBrasil.ipynb`. O README apresenta a metodologia, os principais resultados, insights e conclusões do projeto.

---

# ▶️ Como executar

## Google Colab

O notebook pode ser executado diretamente no Google Colab:

👉 **[Abrir AluraStoreBrasil.ipynb no Google Colab](https://colab.research.google.com/github/Lufsenna/3-fase---1-Desafio-do-Challenge-Alura-Store/blob/main/AluraStoreBrasil.ipynb)**

---

## 💻 Execução local

### 1. Clonar o repositório

```bash
git clone https://github.com/Lufsenna/3-fase---1-Desafio-do-Challenge-Alura-Store.git
```

### 2. Entrar na pasta

```bash
cd 3-fase---1-Desafio-do-Challenge-Alura-Store
```

### 3. Instalar as dependências

```bash
pip install pandas numpy matplotlib folium jupyter
```

### 4. Executar o Jupyter Notebook

```bash
jupyter notebook AluraStoreBrasil.ipynb
```

---

# 💡 Principais insights

A análise dos indicadores permitiu identificar diferenças importantes entre as quatro lojas.

## 🏆 Loja 1 — Maior faturamento

A Loja 1 apresentou:

* **Maior faturamento:** R$ 1.534.509,12;
* **Menor avaliação média:** 3,98;
* **Maior frete médio:** R$ 34,69.

### Interpretação

A Loja 1 possui forte desempenho em faturamento, porém apresenta os indicadores menos favoráveis de **avaliação média e custo de frete**.

Isso indica que existe oportunidade para melhorar a experiência do cliente e a eficiência logística.

---

# ⭐ Loja 3 — Melhor avaliação

A Loja 3 apresentou:

* **Melhor avaliação média:** 4,05;
* **Faturamento:** R$ 1.464.025,03;
* **Frete médio:** R$ 33,07.

### Interpretação

A Loja 3 apresenta o melhor indicador de satisfação entre as quatro unidades.

Apesar de não possuir o maior faturamento, apresenta uma combinação interessante entre desempenho comercial e avaliação dos clientes.

---

# ⚠️ Loja 4 — Menor faturamento

A Loja 4 apresentou:

* **Menor faturamento:** R$ 1.384.497,58;
* **Avaliação média:** 4,00;
* **Menor frete médio:** R$ 31,28.

### Interpretação

A Loja 4 apresenta o **menor faturamento**, mas também possui o **menor custo médio de frete** e uma avaliação média superior à Loja 1.

Portanto, o baixo faturamento deve ser analisado em conjunto com os demais indicadores.

---

# 🎯 Conclusão

Com base nos indicadores analisados, a **Loja 4 apresenta o menor faturamento entre as quatro unidades**, sendo o principal ponto de atenção para a decisão do Senhor João.

Entretanto, a análise demonstra que o faturamento isoladamente não é suficiente para avaliar o desempenho de uma unidade.

A Loja 4 apresenta:

* menor faturamento;
* menor frete médio;
* avaliação média de 4,00.

Enquanto a Loja 1 apresenta:

* maior faturamento;
* menor avaliação média;
* maior frete médio.

Dessa forma, a decisão de encerramento deve considerar o conjunto dos indicadores e não apenas o faturamento.

---

# 📌 Recomendação

Considerando o objetivo específico do desafio — identificar a loja com menor desempenho para uma possível decisão de encerramento — a **Loja 4 é a principal candidata**, principalmente devido ao menor faturamento.

Antes de uma decisão definitiva, entretanto, seria recomendável aprofundar a análise considerando:

* margem de lucro;
* custos operacionais;
* custo logístico;
* quantidade de clientes;
* ticket médio;
* crescimento ao longo do tempo;
* estoque;
* potencial de mercado;
* rentabilidade.

Essa análise complementar permitiria avaliar não apenas o volume de vendas, mas a **rentabilidade e sustentabilidade da unidade**.

---

# 📚 Aprendizados

Este projeto possibilitou desenvolver e aplicar conhecimentos importantes de **Análise de Dados e Ciência de Dados**, incluindo:

* Importação e leitura de dados;
* Organização e tratamento de DataFrames;
* Manipulação de dados com Pandas;
* Operações numéricas com NumPy;
* Agrupamento e agregação de dados;
* Cálculo de médias e totais;
* Análise comparativa;
* Análise exploratória de dados;
* Criação de visualizações;
* Análise geográfica;
* Interpretação de indicadores;
* Identificação de padrões;
* Transformação de dados em insights;
* Comunicação de resultados por meio de storytelling com dados.

---

# 🚀 Próximos passos

Como evolução do projeto, podem ser desenvolvidas novas análises, como:

* análise de margem de lucro;
* análise temporal das vendas;
* ticket médio por loja;
* análise de rentabilidade;
* segmentação de clientes;
* previsão de vendas;
* criação de dashboard em Power BI;
* análise estatística mais aprofundada;
* aplicação de modelos de Machine Learning.

---

# 👨‍💻 Autor

## Luciano Sena

Profissional com mais de **20 anos de experiência nas áreas de Gestão, Vendas, Finanças, Administração e Relacionamento com Clientes**, atualmente em transição para a área de Tecnologia.

Atualmente direcionando a carreira para **Programação, Ciência de Dados, Inteligência Artificial e Machine Learning**.

### Áreas de interesse

* 🐍 Python
* 📊 Data Science
* 🤖 Inteligência Artificial
* 🧠 Machine Learning
* 🗄️ SQL
* 📈 Análise de Dados
* 📊 Business Intelligence
* ☁️ Oracle Cloud
* 🔧 Git & GitHub

---

# 🎓 Formação

Projeto desenvolvido como parte da formação em:

**Oracle Next Education (ONE) / Alura — Data Science**

---

## 🔗 Repositório

**GitHub:** [github.com/Lufsenna](https://github.com/Lufsenna)

---

⭐ **Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório.**
