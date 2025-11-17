# GS-Dynamic

## Alunos
Marchel Augusto Ribeiro de Matos - RM 99856 e
Guilherme Lunghini Teixeira - RM 556892

## 1. Abra o notebook
Você pode rodar o projeto localmente (Jupyter) ou no **Google Colab**:

- Google Colab:  
  **File → Upload Notebook**  
  **ou** importar direto via GitHub

---

## 2. Execute o notebook **de cima para baixo**
Os blocos são independentes, mas exigem ordem:

1. Imports + Decorators  
2. Dataset  
3. GraphValidator  
4. Funções auxiliares  
5. Desafio 1  
6. Desafio 2  
7. Desafio 3  
8. Desafio 4  
9. Desafio 5  
10. Executando Tudo

---

# 📘 Descrição dos “Challenges”

## ✔ **Challenge 1 — DP Recursivo + Monte Carlo**
- Retorna melhor conjunto de habilidades para atingir `S6`
- Respeita limite de tempo (T) e complexidade (C)
- Versão estocástica simula incerteza no mercado

## ✔ **Challenge 2 — Permutações das Skills Críticas**
- Gera as **120** permutações de {S3, S5, S7, S8, S9}
- Verifica grafo (ciclos, órfãos)
- Calcula tempo total incluindo pré-requisitos
- Retorna as **3 melhores ordens**

## ✔ **Challenge 3 — Greedy vs Ótimo**
- Compara seleção por **V/T** com a solução exaustiva
- Demonstra que o greedy pode ser subótimo

## ✔ **Challenge 4 — MergeSort Recursivo**
- Implementação manual usando recursão
- Comparação com sort nativo
- Geração de dois sprints (A e B)

## ✔ **Challenge 5 — Recomendação Inteligente**
- Modelo estocástico de mercado (stable/high)
- Cálculo de valor esperado de sequências futuras
- Recomendação top-3 de habilidades

---

# 📈 Resultados Obtidos (exemplos)

- Melhor caminho determinístico até S6  
- Valor esperado via 300+ simulações MC  
- Melhores 3 permutações das 120  
- Contraexemplo mostrando falha de greedy  
- MergeSort executando com tempos próximos ao sort nativo  
- Recomendação baseada em transições probabilísticas

---

# 📌 Requisitos

- Python 3.8+
- Jupyter Notebook ou Google Colab
- Bibliotecas padrão (`collections`, `typing`, `itertools`, etc.)

Nenhuma instalação extra é necessária.
