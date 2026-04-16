# Priorização de Hipóteses e Análise de Teste A/B

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-7db0ea?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=white)

## 📌 Visão Geral do Projeto
Este projeto tem como foco a priorização de hipóteses de negócios para o aumento de receita e a avaliação rigorosa dos resultados de um Teste A/B. O objetivo foi direcionar esforços para as iniciativas mais promissoras e garantir que as decisões de implementação fossem apoiadas por dados estatísticos confiáveis, livres de distorções causadas por anomalias.

## 🎯 Objetivos de Negócio
* **Otimização de Recursos (Priorização):** Avaliar e ranquear propostas de melhoria utilizando frameworks consolidados no mercado (ICE e RICE) para decidir o que testar primeiro.
* **Avaliação de Performance:** Medir o impacto de uma mudança no produto comparando um grupo de controle (A) com um grupo de teste (B).
* **Tomada de Decisão Estratégica:** Validar estatisticamente se a nova versão aumentou a conversão de clientes ou o ticket médio das compras, recomendando a sua expansão ou o cancelamento do experimento.

## 🛠️ Stack Técnica
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização:** Matplotlib, Seaborn (Gráficos de receita acumulada e dispersão)
* **Estatística Avançada:** SciPy (Testes de significância T-test)

## 📉 Metodologia e Processamento
1. **Priorização com ICE e RICE:** Cálculo do potencial de cada hipótese considerando Impacto, Confiança, Esforço e Alcance (Reach), evidenciando como o tamanho do público-alvo altera a viabilidade de um projeto.
2. **Construção de Métricas Acumuladas:** Agrupamento e cálculo diário de receita, pedidos e visitantes para analisar a estabilidade do Teste A/B ao longo do tempo.
3. **Identificação de Anomalias:** Utilização de gráficos de dispersão e cálculo de percentis para isolar utilizadores com comportamento atípico (número extremo de pedidos ou compras de valores exorbitantes).
4. **Testes Estatísticos (Dados Brutos vs. Filtrados):** Aplicação de testes de hipóteses independentes para avaliar a diferença nas taxas de conversão e no ticket médio, garantindo que os *outliers* não enviesassem as conclusões.

## 🏆 Resultados e Conclusões
* **Relevância do Alcance:** A análise provou que hipóteses com alto impacto podem não ser prioritárias se o seu alcance for de nicho. O framework RICE mostrou-se mais adequado ao evidenciar iniciativas de amplo alcance.
* **Análise de Ticket e Conversão:** Embora os gráficos acumulados iniciais pudessem sugerir alguma variação devido a picos anormais de compras pontuais, a limpeza de anomalias revelou o comportamento real do público.
* **Recomendação Final:** Os testes estatísticos confirmaram que **não há diferença estatisticamente significativa** entre o grupo de controle e o grupo de teste para a métrica de ticket médio e conversão. A recomendação estratégica final foi **interromper os testes**, economizando tempo e verba, para focar nas próximas hipóteses priorizadas da lista.

---

### 📂 Estrutura do Repositório
* `sprint9.ipynb`: Notebook Jupyter com as lógicas de priorização, análise do teste A/B, detecção de outliers e testes estatísticos.
* `dataframes/`: Pasta contendo as bases de dados utilizadas (`hypotheses_us.csv`, `orders_us.csv`, `visits_us.csv`).

---
**João Pedro Vidotto Tavares Dias** *Data Analyst | Especialista em Vendas* [LinkedIn](https://www.linkedin.com/in/joao-vidotto/) | [GitHub](https://github.com/jpvidotto)
