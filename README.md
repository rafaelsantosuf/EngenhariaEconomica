# Calculadora de Fatores de Engenharia Econômica

Este repositório contém um notebook Jupyter chamado `calcula_fatores.ipynb`, desenvolvido para auxiliar no cálculo de **fatores de equivalência em engenharia econômica**, como:

- Fator de valor futuro (F/P)
- Fator de valor presente (P/F)
- Fator de série uniforme (P/A, A/P, A/F, F/A)
- Fator de gradiente uniforme (A/G)

## 📌 Objetivo

Facilitar a análise de alternativas de investimento, projetos e fluxos de caixa por meio do cálculo automatizado dos principais fatores utilizados em engenharia econômica.

## 📂 Estrutura

- `calcula_fatores.ipynb` — notebook interativo com funções para calcular os fatores econômicos, além de exemplos práticos de uso.
- (Opcional) `requirements.txt` — arquivo com dependências, caso o notebook use bibliotecas externas como `numpy` ou `matplotlib`.

## ▶️ Como usar

1. Clone o repositório ou baixe o notebook.
2. Execute o notebook em um ambiente Jupyter, como:
   - Jupyter Notebook
   - JupyterLab
   - Google Colab (recomendado para uso rápido)

3. Utilize as funções fornecidas para calcular os fatores desejados, por exemplo:

```python
c_f('PF', i=10, n=3)  # Calcula Fator P/F com i = 10% e n = 3 anos
