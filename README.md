# 🐼 Pandas Intro — Atividade 2

Exercícios de limpeza, transformação e agrupamento de dados com pandas, usando o dataset de **emendas parlamentares brasileiras**.

## Dataset

**emendas_parlamentares.parquet** — dados abertos sobre emendas individuais ao orçamento federal, com informações de autor, localidade, função, valores empenhados, liquidados e pagos.

> Download: [Google Drive](https://drive.google.com/file/d/19ydA23-eboyiKxN29JL1EQWW4CplTiKg/view?usp=sharing)

## Exercícios

| # | Tópico |
|---|--------|
| 1 | Filtrar emendas de 2022 |
| 2 | Filtro com duas condições (região Norte + valor > 500k) |
| 3 | Filtro por estado (SP ou RJ) |
| 4 | Substituição de valores (`"Sem informação"` → `"Não disponível"`) |
| 5 | Transformação de texto (uppercase) |
| 6 | Detecção e remoção de duplicatas |
| 7 | Remoção de duplicatas por subconjunto de colunas |
| 8 | Identificação de valores nulos |
| 9 | Preenchimento de nulos (`fillna`) |
| 10 | Conversão de tipo (`int` → `str`) |
| 11 | Conversão de tipo (`float`) |
| 12 | Agrupamento e soma por região |
| 13 | Contagem de emendas por função |
| 14 | Criação de coluna derivada (`Saldo a Pagar`) |
| 15 | Remoção de colunas totalmente vazias |
| 16 | Exportação para JSON |

## Como rodar

Abra direto no Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rafael-robsonn/pandas_intro-2/blob/main/pandas_intro_ex2.ipynb)

Ou localmente:

```bash
pip install pandas pyarrow
jupyter notebook pandas_intro_ex2.ipynb
```

## Stack

- Python 3
- pandas
- pyarrow (leitura de `.parquet`)
- Google Colab
