# Flight Price Prediction

Este projeto tem como objetivo **prever o preço de passagens aéreas** com base em variáveis como companhia aérea, origem, destino, classe da viagem, número de escalas, horários de partida e chegada, duração do voo e dias restantes até a viagem, utilizando **Scikit-Learn**.  

O projeto foi desenvolvido para fins de estudo no **Flight Price Prediction Task do Kaggle**.

---

## Dataset

O dataset contém mais de **300 mil registros** de voos entre as principais cidades da Índia.

- **Tamanho:** 300.261 registros  
- **Número de variáveis:** 11  
- **Variável alvo:** `Price` (valor da passagem)  

### Features
- `Airline` → Companhia aérea  
- `Flight` → Identificação do voo  
- `Source City` → Cidade de origem  
- `Destination City` → Cidade de destino  
- `Class` → Classe da viagem (econômica ou executiva)  
- `Stops` → Número de escalas  
- `Departure Time` → Horário de partida  
- `Arrival Time` → Horário de chegada  
- `Duration` → Duração total do voo  
- `Days Left` → Dias restantes até a viagem  

---

## Modelo de IA

O modelo principal utiliza **RandomForestRegressor**, mas outros modelos de regressão podem ser testados para comparação. O pipeline segue as seguintes etapas:

### 1. Data Exploration
- Análise inicial dos dados  

### 2. Pre-Processing
- Conversão de variáveis categóricas em **one-hot encoding**  
- Normalização de variáveis numéricas  
- Feature engineering

### 3. Treinamento do Modelo de Regressão
- Divisão entre **treino e teste**  
- Treinamento do **RandomForestRegressor**  
- Avaliação com métricas: **RMSE**, **MAE** e **R²**    

### 4. Hyperparameter Tuning (em construção)
- Ajuste de parâmetros do Random Forest para otimização de desempenho  

---

## ⚙️ Instalação e Execução


Clone o repositório:
```bash
git clone https://github.com/tarunk04/COVID-19-CaseStudy-and-Predictions.git
```

Abra o Jupyter Notebook e carregue o notebook para acessar as análises e previsões.

---
## Autor

Alisson Moura
