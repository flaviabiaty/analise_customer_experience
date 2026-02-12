# analise_customer_experience
Estudo quantitativo dos principais drivers do NPS e da satisfação do cliente, com foco em eficiência operacional e impacto do tempo de atendimento.
# Customer Experience Analysis – Atendimento e NPS

## Objetivo do Projeto

Este projeto tem como objetivo analisar os principais fatores que impactam a experiência do cliente, com foco em:

- Satisfação do Cliente
- Net Promoter Score (NPS)
- Resolução do Problema
- Tempo de Espera
- Tempo de Resolução
- Quantidade de Reclamações
- Feedback de Sentimento

A análise busca responder:

- O tempo de atendimento impacta a satisfação?
- Existe relação clara entre tempo de atendimento e NPS?
- Quais fatores afetam diretamente o NPS?
- O Feedback de Sentimento é um bom discriminador da experiência do cliente?

---

## Estrutura da Base

Principais variáveis analisadas:

- `Media_NPS`
- `Satisfacao_Cliente`
- `Tempo_Espera`
- `Tempo_Resolucao`
- `Qtd_Reclamacoes`
- `Problema_Solucionado`
- `Feedback_Sentimento`

---

## Métodos Utilizados

- Análise Exploratória de Dados (EDA)
- Correlação de Pearson
- Regressão Logística (Logit)
- Decomposição de Variância
- Information Value (IV)
- Boxplots e visualizações

Bibliotecas principais:

```python
pandas
numpy
seaborn
matplotlib
statsmodels
scipy
