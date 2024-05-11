# Previsão de Carga com Facebook Prophet

Este projeto utiliza o algoritmo de previsão Prophet, desenvolvido pelo Facebook, para prever a demanda de carga elétrica.

## Sobre o Prophet

O Prophet é um procedimento de previsão de séries temporais baseado em um modelo aditivo onde as tendências não lineares se ajustam a sazonalidades anuais, semanais e diárias, além de incluir feriados. Funciona melhor com séries temporais que possuem fortes efeitos sazonais e várias temporadas de dados históricos. O Prophet é robusto para dados faltantes e mudanças de tendências, e geralmente lida bem com outliers.

## Dados de Carga

Este projeto utiliza dados históricos de carga elétrica para treinar o modelo Prophet. Os dados devem estar em um formato tabular com duas colunas:
- `ds`: Timestamp da observação.
- `y`: Valor da carga no timestamp correspondente.

## Pré-processamento de Dados

Antes de treinar o modelo, os dados de carga podem precisar ser pré-processados. Isso pode incluir:

- **Limpeza de dados:** Remover ou imputar dados faltantes ou outliers.
- **Agregação de dados:** Agregar os dados em intervalos de tempo maiores (por exemplo, de hora em hora para diariamente), dependendo do objetivo da previsão.
- **Transformação de dados:** Aplicar transformações matemáticas aos dados para melhorar o desempenho do modelo (por exemplo, aplicar logaritmo).

## Treinamento do Modelo

O modelo Prophet é treinado usando os dados históricos de carga. Os parâmetros do modelo podem ser ajustados para otimizar o desempenho.

## Previsão de Carga

Uma vez treinado, o modelo Prophet pode ser usado para prever a demanda futura de carga. A previsão pode ser feita para qualquer horizonte de tempo.

## Avaliação do Modelo

O desempenho do modelo pode ser avaliado usando várias métricas, como:
- **Erro Quadrático Médio (RMSE)**
- **Erro Absoluto Médio (MAE)**
- **Erro Percentual Absoluto Médio (MAPE)**

## Visualização

Os resultados da previsão podem ser visualizados usando gráficos e tabelas. Isso pode ajudar a entender o desempenho do modelo e identificar quaisquer problemas potenciais.

## Aplicações

Este projeto pode ser usado para diversas aplicações, incluindo:
- Previsão de demanda de energia
- Gerenciamento de risco
- Planejamento de capacidade

## Próximos Passos

Este projeto pode ser expandido de várias maneiras, incluindo:
- Incorporar variáveis externas
- Automatizar o processo de previsão
- Desenvolver um painel interativo

## Contato

Para qualquer dúvida ou sugestão, entre em contato com Luiz Rocha em oi@luizrocha.pro .

