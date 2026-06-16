# Model Fitness — Análise de Rotatividade de Clientes

## Sobre o Projeto

Análise completa de churn para uma rede de academias fictícia, com o objetivo de 
prever quais clientes têm maior probabilidade de cancelar no mês seguinte e 
desenvolver estratégias de retenção baseadas em dados.

## Estrutura da Análise

- **Passo 1** — Carregamento e inspeção dos dados
- **Passo 2** — Análise Exploratória (AED): estatísticas descritivas, histogramas e matriz de correlação
- **Passo 3** — Modelagem preditiva: Regressão Logística vs Random Forest
- **Passo 4** — Clusterização de clientes com K-Means (5 clusters)
- **Passo 5** — Conclusões e recomendações de retenção

## Principais Resultados

- Taxa de churn geral: **26%**
- Melhor modelo: **Regressão Logística** (Acurácia: 91,7% | Recall: 85,4%)
- Clusters de maior risco identificados: clusters 2 e 3 (churn de 51,8% e 44,4%)
- Principais preditores de churn: tempo de contrato restante, lifetime e frequência atual

## Tecnologias Utilizadas

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy

## Como Executar

```bash
git clone https://github.com/msitta/model-fitness-churn-analysis.git
```

Abra o arquivo `churn_analysis.ipynb` em qualquer ambiente Jupyter.

## Autor

Marco Aurélio Martins Sitta  
[LinkedIn](https://www.linkedin.com/in/seu-perfil) | [GitHub](https://github.com/msitta)