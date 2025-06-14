# Análise de Dados Históricos de Fórmula 1

## Objetivo

O objetivo deste projeto é realizar uma análise estatística e exploratória das temporadas
da Fórmula 1, abrangendo o desempenho de pilotos e construtores, o perfil dos
competidores (idade e nacionalidade), além de aspectos técnicos como tempos de volta,
pit stops, e resultados por circuito.

Para mais detalhes sobre o escopo completo e as metas específicas do projeto, consulte o escopo de trabalho completo disponível [aqui](./docs/Escopo_Trabalho_Analise_F1_v1.pdf).

## Questões Analíticas

### Temporadas

- Qual o pódio do campeonato de pilotos e construtores em cada temporada?
- Quais circuitos ocorreram em cada ano e quais foram seus pódios?
- Como foi a evolução dos tempos de volta e pit stops ao longo dos anos?

### Pilotos 

- Quais os 10 pilotos com mais vitórias?
- Quais os 10 pilotos com mais títulos?
- Quais os 10 pilotos com mais corridas participadas?
- Como se comparam dois pilotos em vitórias, pódios, poles etc.?
- Como é a distribuição dos pilotos por nacionalidade?

### Construtores

- Quais as 5 equipes de construtores com mais títulos?
- Quais as 5 equipes de construtores com maior quantidade de vitórias em uma única temporada?
- Quais as 5 temporadas com maior dominância de uma única equipe de construtores?
- Como é a distribuição das equipes por nacionalidade?

### Circuitos

- Quais os 5 pilotos com mais vitórias em cada circuito?
- Qual o pódio de cada circuito da temporada?
- Qual o grid de largada de cada circuito da temporada?
- Quais os tempos de volta e pit stops mais rápidos de cada circuito?
- Como é a distribuição dos circuitos por país?

### Recursos Iterativos e Filtros

- Filtro por ano/temporada.
- Comparação entre dois pilotos.
- Análise por país ou nacionalidade.
- Recorte por circuito específico.

## Descrição dos Dados

- Fonte: Base de dados do [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020). 
- Estrutura dos arquivos: Arquivos .csv.
- Período: 1950 a 2024.

## Pré-processamento e Limpeza de Dados

- Tratamento de nulos.
- Tratamento de duplicatas.
- Conversão de tipos.
- Formatação dos dados.
- Criação de colunas derivadas.

Para mais detalhes sobre a limpeza dos dados, consulte os arquivos de limpeza e o log de mudanças disponível [aqui](./data_cleaning/changelog.md).
