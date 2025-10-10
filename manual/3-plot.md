# Gráficos de Cintilação

Esta seção descreve a funcionalidade de geração personalizada de gráficos de índices de cintilação ionosférica a partir de dados históricos de monitoramento. 

A ferramenta permite visualizar séries temporais de dados que foram coletados desde 2011 por centenas de estações. É possível comparar satélites, comparar estações, exportar os resultados em formato de imagens ou arquivos texto.

> [!TIP]
> O tempo de vida das estações varia conforme o período operativo de cada uma delas. Para checar se determinada estação esteve em funcionamento em determinado período, utilize a opção de Calendar Views ou de Mapa de Estações.



## Como usar (fluxo rápido)

1. Selecione o período de tempo (data/hora de início e de fim);
2. Selecione uma ou mais estações de monitoramento;
3. Selecione os satélites: há opção de selecionar todos os satélites por constelação (ex: selecionar todos os satélites GPS) ou invididualmente pelo PRN (ex: selecionar apenas o satélite G01);
4. Sinal: selecione dentre as opções disponíveis, sendo que:
- Sig1 significa L1CA para GPS / GLONASS / SBAS / QZSS; E1BC para Galileo; B1 para BeiDou;
- Sig2 significa L2C para GPS / GLONASS / QZSS; E5a para Galileo; L5 para SBAS; B2 para BeiDou;
- Sig3 significa L5 para GPS / QZSS; E5b para Galileo.
5. Filtrar a saída: é possível aplicar filtros booleanos sobre o índice que seŕa exibido. Uma sugestão padrão é exibir apenas os valores de índices $S_{4}$ acima de 0.1, reduzindo assim a numerosidade dos pontos na saída gráfica;
6. Máscara de elevação (em graus decimais): filtrar os dados de saída de acordo com o ângulo de elevação dos satélites (sugestão padrão é considerar apenas satélites com ângulo de elevação iguais ou superiores a 10°);
7. Filtrar outros campos (opcional): Adicionalmente, é possível aplicar filtros com operadores booleanos sobre quaisquer parâmetros de monitoramento disponíveis;
8. Rótulos: edite os títulos do gráfico ou dos eixos X e Y.
9. Destacar satélites ou estação: utilize esta opção para alternar entre a identificação dos pontos por cores/símbolos distintos por satélite ou por estação.



