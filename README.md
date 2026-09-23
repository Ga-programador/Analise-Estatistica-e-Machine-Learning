# Checkpoint 5 — Análise Estatística e Machine Learning (Wine Dataset)

## Apresentação do Projeto
Este repositório contém a resolução do **Checkpoint 5 (2º Semestre)** desenvolvido para as disciplinas de **Machine Learning & Modelling** e **Statistical Computing with R & Python** do curso de Inteligência Artificial da FIAP.

O objetivo do projeto é realizar uma análise estatística exploratória e probabilística de variáveis do dataset *Wine*, seguida da aplicação do algoritmo de agrupamento não supervisionado **K-Means** para segmentar os vinhos segundo as suas características químicas.

---

## Integrantes do Grupo
* Aline Delphino Chiaramonte — RM569860
* Gabriel Gomes dos Santos — RM573836
* Gustavo Luiz Vilella Santin - RM573213
* Victor Dias Rodrigues Bandeira de Azevedo — RM574108

---

## Estrutura do Repositório
* `notebook_checkpoint5.ipynb`: Notebook Jupyter/Colab contendo todo o código executado, gráficos e análises detalhadas da Parte 1 e Parte 2.
* `wine-clustering.csv`: Conjunto de dados utilizado no projeto.
* `README.md`: Documentação com a descrição do projeto e instruções de execução.

---

##Conteúdo do Notebook

### Parte 1: Statistical Computing with R & Python
Análise detalhada de duas variáveis quantitativas (`Alcohol` e `Malic_Acid`):
1. **Visualização dos Dados:** Tabelas de distribuição de frequência (Regra de Sturges) e histogramas.
2. **Análise Descritiva:** Média, Mediana, Moda, Variância, Desvio Padrão, Coeficiente de Variação e Quartis ($Q_1, Q_2, Q_3$).
3. **Análise Probabilística:** Cálculos de distribuição de probabilidade e estimativas empíricas.

### Parte 2: Machine Learning & Modelling
Agrupamento não supervisionado dos vinhos:
1. **Pré-processamento:** Tratamento e padronização dos dados com `StandardScaler`.
2. **Seleção de Clusters:** Definição do número ideal de grupos ($K$) utilizando o **Método Elbow** e **Silhouette Score**.
3. **Ajuste do K-Means:** Modelação e atribuição dos rótulos.
4. **Análise de Perfis:** Interpretação das características químicas distintivas de cada cluster de vinho.

---

## Como Executar o Projetos
1. Clone este repositório:
   ```bash
   git clone https://github.com/Ga-programador/Analise-Estatistica-e-Machine-Learning.git
