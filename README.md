# Projeto de Análise e Visualização de Dados de Educação

Este repositório contém o projeto de análise e visualização de dados focado em métricas de educação e socioeconômicas, como o **PISA** (Programa Internacional de Avaliação de Estudantes), **IDH** (Índice de Desenvolvimento Humano) e **PIB per capita**.

O objetivo do projeto é explorar as relações entre essas variáveis em diferentes países, utilizando técnicas de **Análise de Cluster** para segmentar os países em grupos com características semelhantes. A análise culmina na visualização interativa dos resultados em mapas, permitindo uma compreensão clara dos padrões geográficos e da distribuição dos clusters.

## Ferramentas e Bibliotecas Utilizadas

- **Jupyter Notebook**: Ambiente de desenvolvimento para a análise e visualização.
- **Pandas**: Para a manipulação e limpeza dos dados.
- **Scikit-learn**: Para a implementação do algoritmo de K-Means.
- **Seaborn & Matplotlib**: Para a criação de gráficos estatísticos e de dispersão.
- **Folium**: Para a criação de mapas interativos.

## Estrutura do Projeto

A análise foi realizada em um único notebook, que está estruturado da seguinte forma:

1.  **Carregamento e Limpeza de Dados**: Importação e tratamento inicial dos dados de várias fontes.
2.  **Análise Exploratória (EDA)**: Geração de estatísticas descritivas e visualização de correlações entre as variáveis.
3.  **Análise de Cluster com K-Means**:
    - Padronização dos dados.
    - Uso do **Método do Cotovelo** para determinar o número ideal de clusters.
    - Aplicação do algoritmo K-Means para agrupar os países.
4.  **Visualização dos Clusters**:
    - Criação de matrizes de dispersão (pairplots) para visualizar a separação dos clusters.
    - Criação de mapas de calor e mapas de bolhas interativos para exibir os clusters geograficamente.

## Resultados e Visualizações Principais

A análise resultou na identificação de **quatro clusters** distintos, que representam diferentes níveis de desempenho em educação e desenvolvimento socioeconômico. As visualizações geradas são essenciais para entender esses resultados:

-   **Matriz de Dispersão**: Mostra como os clusters se distribuem em relação às variáveis de PISA, IDH e PIB.
-   **Mapa de Calor**: Destaca as áreas geográficas com maior concentração de valores altos (ou baixos) para cada métrica.
-   **Mapa de Bolhas Interativo**: Exibe a localização de cada país, com a cor da bolha representando o cluster ao qual ele pertence. Este mapa permite uma análise visual direta da distribuição dos clusters globalmente.

---



