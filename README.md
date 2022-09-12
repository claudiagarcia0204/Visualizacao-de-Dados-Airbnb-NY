# Visualização de Dados Airbnb NY
 Status: ativo, em andamento

# Contexto 
Airbnb fornece uma plataforma de busca e reservas entre a pessoa que oferece a acomodação e o turista que busca pela locação. Segundo dados "Wikipédia" o site abrange mais de 500 mil anúncios em mais de 35.000 cidades e 192 países.
Desde 2008, hóspedes e anfitriões usam o Airbnb para expandir as possibilidades de viagem. 

# Fato interessante
Segundo informações obtidas no Wikipédia o "Airbnb sofre resistência por setores contrários à chamada economia do compartilhamento. Cidades como Barcelona na Espanha, e Berlim na Alemanha, proibiram o aplicativo, sob o argumento de que ele pode minar setores já estabelecidos da economia, como a rede hoteleira."

# Dados utilizados para visualização - Nova York / EUA
A Listagens dos dados da Airbnb na Cidade de Nova York foram obtidas a partir do site Tableau Public - Fonte: Inside Airbnb

# Métodos utilizados na visualização
Tableau Public

# Tecnologias
Lista com tecnologias utilizadas:
Python
Pd.numpy

# Dicionário
Para melhor compreensão das informações que serão apresentadas, foi criado um dicionários para auxilizar na localização das informações:

* id - número de identificação do imóvel
* name - Título do anúncio da propriedade
* host id - número de identificação do proprietário
* host name - nome do anfitrião
* neighbourhood group - nome do bairro
* neighbourhood - nome da zona de localização
* latitude - coordenada de latitude da propriedade
* longitude - coordenada de longitude da propriedade
* country - código do País
* instant bookable - reserva da propriedade
* cancellation policy - política de cancelamento
* room type - tipo de acomodação oferecida
* construction year - ano de contrução da propriedade
* price - valor do aluguel
* service fee - taxa de serviço
* minimum nights - menor quantidade de noites para locação
* number of reviews - número de reviews
* last review - data do último review
* reviews per month - quantidade de reviews em um mês
* calculated host listings  count - quantidade de imóveis do mesmo anfitrião
* availability 365 - número de dias de disponibilidade dentro de 365 dias


# Descrição da visualização
Com esta análise de dados, buscamos compreender algumas informações sobre o Airbnb na cidades de N.Y
Serão levantados informações sobre:
1. Tipo de acomodação mais destacados
           
2. Média do preço para locação

3. Possibilidade de valor da locação ser maior em locais com pontos turisticos mais relevante


## Perguntas para análise
1. Qual tipo de acomodação é a mais alugada?
2. Qual é o preço médio por tipo de quarto?
3. A pontuação da hospedagem tem influencia com o valor final da hospedagem mais cara?


## Possíveis conclusão
1. Os tipos de acomodação destacados pelo site são:
    Apartamento/Casa inteiras (Entire home/apt)
    Quarto privado (Private room)
    Quarto compartilhado (Shared room)
    Quartos de hotel (Hotel room)        

Os tipos de acomodação estão mais centralizadas em Mathattan e Brooklyn e são as acomodações Apartamento/Casa inteiras (Entire home/apt) e Quarto privado (Private room)
Com a análise apresentada podemos observar que viajar em família, ou em casal, torna mais fácil a localização de hospedagens, já que os tipos de acomodação totalizam:
* Apartamento/Casa inteiras (Entire home/apt) - com 49.542 acomodações
* Quarto privado (Private room) - com 42.447 acomodações

Os 2 tipos de acomodação citados acima, representam cerca de 97% dos imóveis anunciados.

2. A partir do gráfico de preço médio por tipo de quarto podemos destacar a média é de US$ 630,0. Se compararmos com o preço médio de quarto com relação ao bairro, veremos que Queens tem o preço médio mais alto por dia, porém é Manhatthan que detêm o maior número de anfitriões.  

3. Segundo os dados levantados, foi possivel verificar que a pontuação média por bairro não é a questão determinante, pois a variação é pequena entre as os tipos de acomodação.

## Contexto Final

Nesta análise podemos observar que Manhattan detem o maior numero de anfitriões e que o tipo mais comum de acomodação é o de casa/apto completo. Uma das justificativas para este número elevado de acomodações em Manhattan, pode ser por 80% das atraçoes de Nova York estarem concentrados neste bairro. 

Em relação ao preço, Queens detém os maiores valores para locação por dia. Sua economia se baseia na arte, no turismo e nesta região estão os aeroportos JFK e LaGuardia.
Uma das possíveis respostas para verificação de preço médio mais elevado no Queens, além da economia mais diversificada dos cinco distritos da cidade de Nova York. O Queens é o lar do Aeroporto Internacional John F. Kennedy e do Aeroporto LaGuardia, ambos entre os mais movimentados do mundo, que pode contribuir na elevação do valor da locação.

Staten Island é o único bairro não conectado ao sistema de metrô da cidade de Nova York. O Staten Island utiliza o serviço de balsa (Ferry) gratuito conectando o bairro a Manhattan através do porto de Nova York. Staten Island é excelente para locatários que gostam de economizar e buscam uma melhor classificação de acomodações. 

## Link do Tableau
https://public.tableau.com/app/profile/claudia.garcia6864/viz/TrabalhodeVisualizaoAirbnb/Dashboard?publish=yes

Contato
linkedin: linkedin.com/in/claudia-garcia-765b5037

github: @claudiagarcia0204
