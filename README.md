## US_house_price_analysis 
  Status do projeto (em andamento)

## Objetivo
  O objetivo desse projeto é extrair dados através de uma API e gerar uma análise a partir destes dados. 
  Usei a API do do FRED (dados econômicos do Federal Reserve Bank of St. Louis) para comparar índices financeiros com o preço dos imóveis nos USA.
    
## Técnicas
  - Extração
  - Limpeza e processamento
  - Visualização
  - Exportação
 
## Bibliotecas 
  - Python
  - Fredapi
  - Pandas
  - Numpy
  - Datetime
  - Sklearn.preprocessing
  - Matplotlib
  - Plotly.express
  - Seaborn
    
## Ferramenta
  - Jupyter
  
## Etapas
  - No site https://research.stlouisfed.org/ pesquisei e identifiquei os dados que pudessem me ajudar a descobrir os índices cuja variação tem maior correlação com o índice dos preços dos imóveis nos Estados Unidos.
 - Filtre os dados do S&P 500 para converter informações diárias em mensais e poder comparar com os índices com informação mensal. Fiz o mesmo processo com a taxa de juros.
 - Juntei todas as informações em um único dataframe.
 - Usei MinMaxScaler para normalizar os valores que foram utilizados nos gráficos.
 - Exportei os dados para o banco de dados no MySQL.
 - Fiz envio automático de e-mail com as informações diárias.
 - Gerei arquivo de log.

## Conclusão
 - Observei que nos últimos 10 anos a evolução do índice de preço dos imóveis acompanhou a evolução do S&P 500 (um dos principais indicadores de ações norte-americanas, seria equivalente ao Ibovespa aqui no Brasil).

![image](https://user-images.githubusercontent.com/112282677/207201190-ae5bfa80-a3b3-45b2-9c9e-ca70c812983b.png)

 - Inflação e Taxa de Juros não apresentaram impacto expressivo no preço dos imóveis. Porém, vale ressaltar que inflação alta é uma situação nova nos USA, sendo recomendável repetir essa análise nos próximos meses para tirar uma conclusão mais precisa.
 
 ![image](https://user-images.githubusercontent.com/112282677/207202351-37e8ba32-6a52-4d34-adb6-0f04a8a18bb0.png)

![image](https://user-images.githubusercontent.com/112282677/207202414-859dcf3a-be5f-4f69-bdb2-eb485f36a9aa.png)

 - Exceto pelo pico de desemprego em 2020, o comportamento está dentro do esperado. Desemprego baixo, preço dos imóveis mais alto, desemprego alto, preço dos imóveis mais baixo. Essa relação é bem visível no gráfico entre 2013 e 2019.
 
 ![image](https://user-images.githubusercontent.com/112282677/207202975-c54ef846-41c9-49f6-9011-7680b57f3498.png)
 
   - Essa foi uma análise introdutória para obter alguns insights. Como próximos passos, poderíamos, por exemplo, segmentar por regiões e verificar se o comportamento foi igual em todo o país.


📫 Se você tiver algum comentário ou sugestão, por favor me avise!
    
    https://www.linkedin.com/in/lenagrumbach/
    
    lenagrumbach@gmail.com

