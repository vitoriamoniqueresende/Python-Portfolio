Neste projeto, utilizei uma base de dados fictícia (T1.CSV) contendo informações sobre o funcionamento de diversas turbinas eólicas, com o objetivo de entender seu desempenho e estabelecer limites aceitáveis de funcionamento.

Utilizando as bibliotecas Pandas, Matplotlib e Seaborn, realizei a importação e tratamento dos dados, realizando alterações nos tipos, nomes e quantidade de colunas conforme necessário.

Após o tratamento dos dados, passei para a análise gráfica, utilizando o modelo de gráfico scatterplot. Este modelo permitiu estabelecer uma relação entre a velocidade do vento medida em metros por segundo e a potência ativa das turbinas.

Durante a análise, ficou evidente que existe uma discrepância entre a potência ideal teórica e a potência real das turbinas. Algumas delas estavam dentro do funcionamento esperado, enquanto outras estavam fora deste padrão.

Para melhor compreender essa situação, criei parâmetros de limite com base na correlação entre a velocidade do vento e a potência ativa das turbinas. Isso me permitiu identificar quantas turbinas estavam dentro e fora dos limites de potência esperada, assim como aquelas que não estavam obtendo a potência desejada.
