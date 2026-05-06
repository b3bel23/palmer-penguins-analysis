# 🐧 Palmer Penguins Data Analysis

Projeto de análise exploratória de dados utilizando o dataset **Palmer Penguins**, com foco em tratamento de dados ausentes, imputação e normalização de variáveis utilizando Python.

---

## 📌 Sobre o projeto

O projeto foi desenvolvido com o objetivo de aplicar técnicas de:

* Análise Exploratória de Dados (EDA)
* Tratamento de dados ausentes
* Imputação de valores
* Normalização de dados
* Manipulação de datasets em Python

O dataset utilizado foi o famoso **Palmer Penguins**, frequentemente utilizado em estudos de ciência de dados e machine learning.

---

## 🧠 Objetivos do projeto

O projeto busca analisar características dos pinguins presentes no dataset, além de simular e tratar problemas comuns em bases de dados reais, como valores ausentes.

Durante o desenvolvimento, foram aplicadas técnicas para:

* Remover valores aleatoriamente da base
* Identificar dados faltantes
* Aplicar imputação utilizando KNN
* Normalizar variáveis numéricas
* Explorar padrões nos dados

---

## ⚙️ Funcionalidades

✅ Carregamento do dataset

✅ Remoção aleatória de valores

✅ Identificação de dados ausentes

✅ Separação entre variáveis categóricas e numéricas

✅ Imputação utilizando KNNImputer

✅ Normalização com MinMaxScaler

✅ Análise exploratória dos dados

✅ Visualização gráfica das informações

---

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Estrutura do projeto

```txt id="40gqmk"
📁 palmer-penguins-analysis
 ┣ 📄 Trabalho2_MD.ipynb
 ┣ 📄 README.md
 ┗ 📄 requirements.txt
```

---

## 📊 Dataset utilizado

O projeto utiliza o dataset **Palmer Penguins**, disponível através da biblioteca Seaborn.

O conjunto de dados contém informações sobre diferentes espécies de pinguins, incluindo:

* Espécie
* Ilha
* Comprimento do bico
* Profundidade do bico
* Comprimento da nadadeira
* Massa corporal
* Sexo

---

## 🔍 Técnicas aplicadas

### 📌 Imputação de dados ausentes

Foi utilizada a técnica de imputação com:

```python id="5t4ky0"
KNNImputer
```

O algoritmo estima valores ausentes com base nos vizinhos mais próximos da base de dados.

---

### 📌 Normalização dos dados

Os dados numéricos foram normalizados utilizando:

```python id="94hq8p"
MinMaxScaler
```

Essa técnica ajusta os valores para uma escala padronizada.

---

## ▶️ Como executar

### 1️⃣ Instale as bibliotecas necessárias

```bash id="q4q60y"
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

### 2️⃣ Execute o notebook

Abra o arquivo `.ipynb` no:

* Jupyter Notebook
* Google Colab
* VS Code

---

## 📚 Conceitos aplicados

* Ciência de Dados
* Pré-processamento de dados
* Análise exploratória
* Machine Learning
* Tratamento de valores ausentes
* Normalização de dados
* Visualização de dados

---

## 🎓 Objetivo acadêmico

O projeto foi desenvolvido com foco acadêmico para praticar técnicas fundamentais de preparação e análise de dados utilizadas em ciência de dados e aprendizado de máquina.

---

## 🚀 Autor

Desenvolvido por **Isabel Baungartner**, **Julia de Souza Leandro**, **Maria Eduarda Fonseca Nascimento** e **Lavinia Oliveira dos Santos**

🎓 Ciência de Dados e Inteligência Artificial — PUC Campinas
