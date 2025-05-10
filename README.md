# 📊 Teste de Hipótese: Diferença Salarial por Gênero

Este projeto aplica estatística inferencial para investigar se há **diferença significativa entre os salários de homens e mulheres** usando um dataset real.

## 📁 Fonte dos dados

- Kaggle: [Salary Dataset – Mohith Sairam Reddy](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data)

## 🎯 Objetivo

Responder à pergunta:  
**“Mulheres recebem salários significativamente diferentes dos homens no mercado de trabalho?”**

## 🧪 Hipóteses estatísticas

- **H₀ (Hipótese Nula):** Não há diferença significativa entre os salários de homens e mulheres.
- **H₁ (Hipótese Alternativa):** Há uma diferença significativa entre os salários de homens e mulheres.

## ⚙️ Metodologia

1. Análise exploratória dos dados (EDA)
2. Verificação da normalidade (teste de Shapiro-Wilk)
3. Escolha do teste estatístico apropriado
4. Teste de hipótese com **Mann-Whitney U Test**

## 📈 Resultado

- **Estatística U de Mann-Whitney:** 4.722.562,50  
- **p-valor:** < 0.0001  
- **Conclusão:** Rejeitamos a hipótese nula.  
Há evidências estatísticas fortes de que existe **diferença significativa entre os salários de homens e mulheres**.

## 📌 Bibliotecas utilizadas

- pandas
- numpy
- matplotlib
- seaborn
- scipy.stats

## 🧠 O que aprendi

- Aplicar testes de normalidade e hipótese corretamente
- Escolher o teste adequado conforme o tipo de dado
- Interpretar p-valores e estatísticas em contexto de negócios
- Documentar e versionar um projeto completo no GitHub

## 🚀 Como executar

```bash
pip install -r requirements.txt
