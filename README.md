# Otimização de Rotas de Transporte - NYC Taxi Trip Duration

## Descrição do Projeto
Este projeto visa otimizar as rotas de transporte de táxis na cidade de Nova York, utilizando o conjunto de dados NYC Taxi Trip Duration. O objetivo principal é desenvolver modelos de Machine Learning para prever a duração das viagens de táxi, possibilitando uma melhoria na eficiência das rotas e uma redução no tempo total de viagem.

## Dataset
O conjunto de dados utilizado neste projeto é fornecido pela Comissão de Táxi e Limusine de Nova York (TLC), e foi amostrado e limpo para os propósitos desta análise. Ele inclui informações detalhadas sobre viagens de táxi em 2016, como coordenadas geográficas de origem e destino, número de passageiros, e timestamps de coleta e entrega.

 - Fonte dos dados: Kaggle - NYC Taxi Trip Duration (https://www.kaggle.com/c/nyc-taxi-trip-duration)
 - Descrição dos arquivos:
    - train.csv - Conjunto de treinamento (1.458.644 registros)
    - test.csv - Conjunto de testes (625.134 registros)
    - sample_submission.csv - Arquivo de envio de exemplo

## Campos de Dados
- id - Identificador exclusivo para cada viagem
- vendor_id - Código do provedor associado ao registro de viagem
- pickup_datetime - Data e hora em que a viagem começou
- dropoff_datetime - Data e hora em que a viagem terminou
- passenger_count - Número de passageiros no veículo
- pickup_longitude - Longitude do ponto de partida
- pickup_latitude - Latitude do ponto de partida
- dropoff_longitude - Longitude do ponto de chegada
- dropoff_latitude - Latitude do ponto de chegada
- store_and_fwd_flag - Indicador de se o registro foi armazenado antes de ser enviado
- trip_duration - Duração da viagem em segundos (variável alvo)

## Objetivo
O objetivo do projeto é desenvolver modelos preditivos que possam prever a duração total das viagens de táxi em Nova York com precisão. Isso pode ajudar a melhorar o planejamento logístico e a otimização de rotas para serviços de transporte.

## Métricas de Avaliação
A métrica utilizada para avaliar a performance dos modelos é o Root Mean Squared Logarithmic Error (RMSLE).

## Instalação

### Requisitos

Para rodar este projeto, você precisará ter os seguintes pacotes instalados:

 - NumPy
 - Pandas
 - Scikit-learn
 - XGBoost
 - Matplotlib
 - Seaborn
 - haversine