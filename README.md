# Tech Challenge - PosTech FIAP AI4DEVS 9IADT - Grupo 20 - Análise de Saúde Mental

## Descrição do Projeto
Este projeto tem como objetivo analisar dados relacionados à saúde mental, explorando fatores que podem influenciar o tratamento.

Através de técnicas de análise exploratória e modelagem de dados, buscamos identificar padrões relevantes e gerar insights que possam contribuir para uma melhor compreensão do cenário.

---

## Dataset
https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset

---

## Objetivos
- Realizar limpeza e tratamento dos dados
- Explorar variáveis relevantes para saúde mental
- Identificar padrões e correlações
- Preparar os dados para modelagem preditiva
- Avaliar fatores que influenciam a busca por tratamento

---

## Estrutura do Notebook
O notebook está organizado nas seguintes etapas:

1. **Importação de Bibliotecas**
2. **Carregamento dos Dados**
3. **Análise Exploratória (EDA)**
4. **Tratamento de Dados**
   - Remoção de valores inconsistentes (ex: "Maybe")
   - Limpeza de variáveis irrelevantes (ex: Occupation)
5. **Visualizações**
6. **Preparação para Modelagem**
7. **Conclusões**

---

## Tratamento de Dados
Durante a análise, algumas decisões importantes foram tomadas:

- A variável **Occupation** foi removida por não apresentar relevância para a variável alvo.
- Valores ambíguos como **"Maybe"** foram excluídos para tornar a análise mais objetiva.
- Foco nas categorias claras: **"Yes"** e **"No"**.

---

## Principais Insights
- Nem todas as variáveis coletadas impactam diretamente a saúde mental.
- Dados ambíguos podem prejudicar a qualidade da análise.
- A limpeza adequada dos dados melhora significativamente a performance analítica.

---

## Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn (se aplicável)
