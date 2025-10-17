# 🧭 PPGEEC2327 — Predição de Séries Temporais com Inteligência Artificial

Repositório da disciplina PPGEEC2327 — Predição de Séries Temporais com Inteligência Artificial, oferecida pelo professor Tiago Barros através do Programa de Pós-Graduação em Engenharia Elétrica e Computação da Universidade Federal do Rio Grande do Norte (UFRN).

Este repositório reúne os projetos desenvolvidos durante a disciplina, com foco na aplicação de modelos clássicos e modernos de previsão em diferentes tipos de séries temporais.

---

## 🗂️ Estrutura geral

PPGEEC2327-timeseries-forecast/
├── LICENSE
├── README.md
├── Projeto_1/
│   ├── data/
│   │   ├── PEMS03/
│   │   ├── PEMS04/
│   │   ├── PEMS07/
│   │   └── PEMS08/
│   ├── output_figures/
│   ├── notebook_v3.ipynb
│   ├── README.md          ← explicação detalhada do projeto
├── Projeto_2/
│   └── (reserva para o próximo estudo)
├── Projeto_3/
│   └── (reserva para o próximo estudo)
└── requirements.txt

---

## 🧩 Projetos

### 🔹 Projeto 1 — Previsão de fluxo de tráfego (PEMS)
Estudo de previsão de tráfego veicular utilizando os conjuntos de dados **PEMS** (California PeMSD3, D4, D7, D8).  
O objetivo é comparar o desempenho de modelos clássicos de séries temporais — **ARIMA**, **SARIMA** e **Holt–Winters** — aplicados ao fluxo médio horário de veículos.

- **Técnicas aplicadas:**  
  Diferenciação sazonal, transformações logarítmica e Box-Cox, decomposição ACF/PACF, e seleção de modelos via AIC/BIC.
- **Métricas de avaliação:**  
  MAE, RMSE, MAPE e R².
- **Principais resultados:**  
  O modelo **SARIMA(2,0,2)×(1,1,1,24)** apresentou o melhor equilíbrio entre erro e estabilidade, com R² ≈ 0.90.

📄 [Acesse a documentação completa do Projeto 1](./Projeto_1/README.md)

---

### 🔹 Projeto 2 — (Reservado)
Espaço destinado ao segundo estudo de caso da disciplina.  
*(a ser definido)*

---

### 🔹 Projeto 3 — (Reservado)
Espaço destinado ao terceiro estudo de caso da disciplina.

---

## ⚙️ Configuração do ambiente

Crie o ambiente virtual e instale as dependências:

```bash
conda create -n ppgeec2327 python=3.11.11 -y
conda activate ppgeec2327
pip install -r requirements.txt
```

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.