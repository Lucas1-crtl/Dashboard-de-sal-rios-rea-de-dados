# 📊 Dashboard de Salários na Área de Dados

Este projeto consiste em um **dashboard interativo desenvolvido com Streamlit** para análise de salários na área de dados ao longo dos anos. A aplicação permite explorar informações salariais de forma visual e dinâmica, utilizando filtros e gráficos interativos com **Plotly**.

## 🎯 Objetivo do Projeto

O objetivo principal é **facilitar a análise exploratória de dados salariais** na área de dados, permitindo responder perguntas como:

* Quais cargos possuem os maiores salários médios?
* Como os salários se distribuem ao longo dos anos?
* Qual a proporção de trabalho remoto?
* Como varia o salário de Cientistas de Dados entre países?

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Streamlit** – construção do dashboard
* **Pandas** – manipulação e análise de dados
* **Plotly Express** – visualizações interativas

## 📂 Estrutura do Projeto

```bash
📁 dashboard_salarios_dados
│
├── app.py              # Aplicação principal em Streamlit
├── README.md           # Documentação do projeto
└── requirements.txt    # Dependências do projeto
```

## 📊 Funcionalidades do Dashboard

### 🔍 Filtros Interativos (Barra Lateral)

* Ano
* Senioridade
* Tipo de contrato
* Tamanho da empresa

Os filtros permitem refinar os dados exibidos em tempo real.

### 📈 Métricas (KPIs)

* Salário médio anual (USD)
* Salário máximo
* Total de registros
* Cargo mais frequente

### 📉 Visualizações

* **Top 10 cargos por salário médio** (gráfico de barras horizontal)
* **Distribuição dos salários** (histograma)
* **Proporção dos tipos de trabalho** (remoto, híbrido, presencial)
* **Mapa mundial** com salário médio de Cientistas de Dados por país

### 📋 Tabela de Dados

* Visualização completa do DataFrame filtrado

## ▶️ Como Executar o Projeto

### 1️⃣ Clone o repositório

```bash
git clone https://github.com/vqrca/dashboard_salarios_dados.git
cd dashboard_salarios_dados
```

### 2️⃣ Crie e ative um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

### 3️⃣ Instale as dependências

```bash
pip install -r requirements.txt
```

### 4️⃣ Execute a aplicação

```bash
streamlit run app.py
```



