# Predict-5Sensors-LSTM

Este script tem como objetivo visualizar as previsões realizadas por um modelo de aprendizado de máquina para dados de sensores, permitindo uma comparação entre os valores reais e os previstos após o processo de inversão da normalização.

Inversão da Transformação dos Dados Os valores previstos são convertidos de volta para sua escala original usando o mesmo objeto scaler que foi utilizado durante a etapa de pré-processamento.

Visualização das Previsões São geradas duas curvas: uma representando os dados reais do sensor e outra com os dados previstos pelo modelo. A visualização é feita com o pacote matplotlib e apresenta:

Linha azul para os dados reais do sensor 1.

Linha laranja para os dados previstos.

Configurações do Gráfico O gráfico inclui título, legenda, rótulos nos eixos e grade para facilitar a interpretação dos dados. Ele mostra a performance do modelo em relação ao sensor 1 e permite observar possíveis desvios ou tendências entre os dados reais e previstos.

Este tipo de visualização é útil para avaliar a precisão de modelos preditivos em séries temporais de sensores industriais, ambientais ou qualquer outro contexto de monitoramento contínuo.
