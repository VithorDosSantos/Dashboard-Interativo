# Dashboard Interativo de Dados de Estudantes

Este projeto é um dashboard interativo desenvolvido com o framework Dash do Python para visualizar e explorar dados relacionados à educação e ao sucesso na carreira. O dashboard permite que os usuários filtrem os dados por campo de estudo e gênero, exibindo diversos gráficos e estatísticas para revelar tendências e insights.

## Funcionalidades

- **Filtros Dropdown**: Selecione um campo de estudo específico e um ou mais gêneros para filtrar o conjunto de dados.
- **Visualizações**:
  - Gráficos de dispersão (ex.: Pontuação SAT vs. Salário Inicial, Média Universitária vs. Ofertas de Emprego).
  - Gráfico de caixa (Satisfação na Carreira por Nível de Cargo).
  - Gráfico de barras (Equilíbrio Trabalho-Vida por Campo de Estudo).
  - Gráfico de pizza (Proporção de Empreendedores).
  - Gráfico de área (Anos para Promoção vs. Pontuação de Networking).
  - Histograma (Distribuição das Pontuações SAT).
- **Tabela de Estatísticas**: Exibe estatísticas descritivas do conjunto de dados filtrado.
- **Análise de Tendência**: Mostra a correlação entre Pontuação SAT e Salário Inicial para o campo selecionado.
- **Tema Escuro**: Utiliza um tema escuro personalizado com gradiente e detalhes em ciano para um visual moderno.

## Pré-requisitos

Para executar este dashboard, você precisa das seguintes bibliotecas Python instaladas:

- `dash`
- `plotly`
- `pandas`

Instale-as usando o pip:

```bash
pip install dash plotly pandas
