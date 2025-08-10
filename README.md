# Dashboard de Salários na Área de Dados

Este projeto é um dashboard interativo desenvolvido com **Streamlit** para análise de dados salariais na área de dados. Ele permite explorar informações de salários anuais em USD, segmentados por ano, senioridade, tipo de contrato, tamanho da empresa e outras variáveis relevantes.

---

## Funcionalidades

- Filtros dinâmicos para refinar a análise com base em:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa

- Visualizações interativas com Plotly:
  - Top 10 cargos por salário médio (gráfico de barras horizontal)
  - Distribuição de salários anuais (histograma)
  - Proporção dos tipos de trabalho (trabalho remoto ou presencial) (gráfico de pizza)
  - Salário médio de Cientista de Dados por país (mapa coroplético)

- Métricas principais exibidas:
  - Salário médio
  - Salário máximo
  - Total de registros
  - Cargo mais frequente

- Tabela interativa com os dados detalhados filtrados.

---

## Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly Express](https://plotly.com/python/plotly-express/)

---

## Como executar o projeto

1. Clone este repositório:

   git clone https://github.com/camilafeldantunes/Dashboard_Imersao.git

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

    python -m venv .venv
    .\.venv\Scripts\activate

3. Instale as dependências:

    pip install -r requirements.txt

4. Execute o dashboard:

    streamlit run nome_do_arquivo.py




