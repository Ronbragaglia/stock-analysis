# 📈 Stock Analysis: Análise Técnica de Ações com Python

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![yfinance](https://img.shields.io/badge/yfinance-Market%20Data-00B09B?style=for-the-badge&logoColor=white)](https://pypi.org/project/yfinance/)
[![Pandas](https://img.shields.io/badge/Pandas-Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-11557c?style=for-the-badge)](https://matplotlib.org/)
[![Colab](https://img.shields.io/badge/Google%20Colab-Ready-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)](https://colab.research.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> Análise técnica completa de ações da bolsa com Python: coleta dados históricos via yfinance e calcula **SMA**, **RSI** e métricas de retorno com visualizações profissionais.

---

## ✨ Funcionalidades

- 📊 **Preço histórico**: gráfico de fechamento com série temporal completa
- 📉 **Médias Móveis (SMA)**: SMA 20 e SMA 50 dias sobrepostas no preço
- ⚡ **RSI (Índice de Força Relativa)**: com linhas de sobrecompra (70) e sobrevenda (30)
- 📦 **Distribuição de retornos diários**: histograma com curva de densidade
- 🔄 **Qualquer ticker**: basta trocar o símbolo (AAPL, PETR4.SA, MGLU3.SA...)

---

## 📸 Gráficos Gerados

### Preço de Fechamento + Médias Móveis
![Preço e SMA](https://github.com/user-attachments/assets/6c01ddaa-2c1e-405c-843b-e5dbf503ab02)

### Distribuição dos Retornos Diários
![Retornos](https://github.com/user-attachments/assets/84df4472-b66c-4e17-a0b5-a5a8702b94e3)

### RSI com Zonas de Sobrecompra/Sobrevenda
![RSI](https://github.com/user-attachments/assets/7f0f71e7-0bcf-4ff1-9f29-957b69702c7f)

### Volume de Negociação
![Volume](https://github.com/user-attachments/assets/38e6ace3-b540-495d-a55f-5d21f2e1c1d7)

### Análise Completa
![Completo](https://github.com/user-attachments/assets/a40ba7bc-d21a-431f-9ac3-395c33cfa6bd)

---

## 🛠️ Tech Stack

| Componente | Tecnologia |
|-----------|-----------|
| Dados de mercado | yfinance |
| Manipulação de dados | Pandas + NumPy |
| Visualização | Matplotlib + Seaborn |
| Ambiente | Google Colab / Jupyter |

---

## 🚀 Como Usar

### Google Colab (recomendado)
Abra o notebook no Colab: o yfinance já é instalado automaticamente.

### Local
```bash
git clone https://github.com/Ronbragaglia/stock-analysis.git
cd stock-analysis
pip install yfinance pandas matplotlib seaborn
jupyter notebook
```

### Analisar outro ticker
No notebook, altere:
```python
ticker = 'PETR4.SA'   # Petrobras
# ou
ticker = 'VALE3.SA'   # Vale
# ou
ticker = 'MSFT'       # Microsoft
```

---

## 📐 Indicadores Implementados

| Indicador | Descrição |
|----------|-----------|
| **SMA 20** | Média Móvel Simples de 20 dias: tendência curta |
| **SMA 50** | Média Móvel Simples de 50 dias: tendência média |
| **RSI 14** | Força relativa: >70 sobrecomprado, <30 sobrevendido |
| **Retorno diário** | Variação % diária com distribuição estatística |

---

## 📁 Estrutura

```
stock-analysis/
├── stock_analysis.ipynb   # Notebook principal
└── README.md
```

---

## 🤝 Contribuições

Pull requests são bem-vindos! Sugestões: adicionar MACD, Bollinger Bands ou backtesting.

---

<div align="center">
  <sub>Feito com 📈 por <a href="https://github.com/Ronbragaglia">Rone Bragaglia</a> · ML Engineer & Fundador <a href="https://cobrancaauto.com.br">CobrançaAuto</a></sub>
</div>
