# Machine Learning — Regressão Linear de Ponta a Ponta

Construção de um modelo preditivo do zero, cobrindo todo o fluxo de um problema supervisionado: do
tratamento dos dados à avaliação do modelo. O projeto usa Regressão Linear (scikit-learn) para
demonstrar, na prática, cada etapa de um pipeline de Machine Learning — da exploração inicial à
interpretação das predições.

> **Nota de confidencialidade:** os dados presentes neste repositório são fictícios, gerados apenas
> para demonstração. Nenhum dado real, credencial ou informação de terceiros foi incluído aqui.

---

## Visão Geral

O projeto documenta um pipeline supervisionado completo em um notebook: importação e exploração dos
dados, tratamento de valores ausentes, pré-processamento, divisão treino/teste, treinamento do modelo
e avaliação por R². O objetivo é mostrar domínio do método, não apenas o resultado — cada passo é
explicado e interpretado.

## Relevância para o Negócio

Regressão é a base de qualquer previsão quantitativa aplicável ao varejo: estimar demanda, projetar
vendas ou entender o efeito de variáveis sobre um resultado. Dominar o fluxo completo — preparar o
dado, treinar e avaliar com honestidade estatística — é o que permite levar um modelo do estudo para
uma decisão real.

## Fluxo do Projeto

| # | Etapa | Descrição |
|---|-------|-----------|
| 1 | Importação | Bibliotecas de dados e modelagem (pandas, NumPy, scikit-learn). |
| 2 | Carregamento | Leitura da base de dados. |
| 3 | Exploração | Estatísticas descritivas e estrutura dos dados. |
| 4 | Dados faltantes | Verificação e tratamento de valores ausentes. |
| 5 | Pré-processamento | Codificação de variáveis, padronização e limpeza. |
| 6 | Split | Divisão treino/teste (`train_test_split`). |
| 7 | Modelagem | Treinamento de `LinearRegression`. |
| 8 | Avaliação | Desempenho medido por R² (`r2_score`). |
| 9 | Predições | Predições e interpretação dos resultados. |
| 10 | Visualização | Comunicação dos achados por gráficos. |

## Stack

Python - scikit-learn - pandas - NumPy - seaborn - Matplotlib - Plotly - Jupyter.

## Como Rodar

```bash
pip install scikit-learn pandas numpy seaborn matplotlib plotly
jupyter notebook 16_MACHINE_LEARNING.ipynb
```

## Estrutura do Projeto

```text
16_MACHINE_LEARNING.ipynb   -> Notebook completo (preparação, modelagem e avaliação)
```

## Autor

José Vitor Santos Pinheiro — Análise de Dados e Inteligência Comercial (Varejo e Supply Chain).
Contato: vytorsantt@gmail.com
