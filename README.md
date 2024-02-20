# Análise de Sentimentos com Language Studio no Azure AI

Neste exercício, foram explorados os recursos da linguagem Azure AI analisando alguns exemplos de avaliações de hotéis. Nele, usei o Language Studio para entender se as avaliações são em sua maioria positivas ou negativas.

## Analisando texto com Language Studio

### Primeiro exemplo

Para iniciar, utilizei o primeiro texto de exemplo do desafio proposto.

 "Tired hotel with poor service
 The Royal Hotel, London, United Kingdom
 5/6/2018
 This is an old hotel (has been around since 1950's) and the room furnishings are average - becoming a bit old now and require changing. The internet didn't work and had to come to one of their office rooms to check in for my flight home. The website says it's close to the British Museum, but it's too far to walk."

Selecionei o idioma, inseri o texto na caixa e após isso cliquei em "Run".

 ![](/content/content-01.png)

 A saída obtida foi a seguinte: 

 ![](/output/s1.1.png)

Então, temos:

 Sentimento:
 Negativo -> 98.00%; Confiança -> 0.00%;

 Opinião:
 Alvo -> Hotel; Avaliações -> Entediante (Negativo, 99.00%);

Opinião:
 Alvo -> Serviço; Avaliações -> Pobre (Negativo, 99.00%);

### Segundo exemplo

Agora, vamos para o texto do segundo exemplo.

" Good Hotel and staff
 The Royal Hotel, London, UK
 3/2/2018
 Clean rooms, good service, great location near Buckingham Palace and Westminster Abbey, and so on. We thoroughly enjoyed our stay. The courtyard is very peaceful and we went to a restaurant which is part of the same group and is Indian ( West coast so plenty of fish) with a Michelin Star. We had the taster menu which was fabulous. The rooms were very well appointed with a kitchen, lounge, bedroom and enormous bathroom. Thoroughly recommended."

 Selecionei o idioma, inseri o texto na caixa e após isso cliquei em "Run".

 ![](/content/content-02.png)

 A saída obtida foi a seguinte:

 ![](/output/s2.1.png)

 Então, temos:

Sentimento: Positivo -> 96.00%; Confiança -> 96.00%;

Opinião: Alvo -> Hotel; Avaliações -> Bom (Positivo, 100.00%);

Opinião: Alvo -> Funcionários; Avaliações -> Bom (Positivo, 100.00%);

### Terceiro exemplo

Agora, vamos para o texto do terceiro exemplo.

"Very noisy and rooms are tiny The Lombard Hotel, San Francisco, USA 9/5/2018 Hotel is located on Lombard street which is a very busy SIX lane street directly off the Golden Gate Bridge. Traffic from early morning until late at night especially on weekends. Noise would not be so bad if rooms were better insulated but they are not. Had to put cotton balls in my ears to be able to sleep–was too tired to enjoy the city the next day. Rooms are TINY. I picked the room because it had two queen size beds–but the room barely had space to fit them. With family of four in the room it was tight. With all that said, rooms are clean and they’ve made an effort to update them. The hotel is in Marina district with lots of good places to eat, within walking distance to Presidio. May be good hotel for young stay-up-late adults on a budget"

Selecionei o idioma, inseri o texto na caixa e após isso cliquei em "Run".

![](/content/content-03.png)

A saída obtida foi a seguinte:

![](/output/s3.1.png)

Então, temos:

Sentimento: Negativo -> 97.00%; Confiança -> 0.00%;

Opinião: Alvo -> Salas; Avaliações -> Pequenas (Negativo, 100.00%);

## Links

[Analize textos com o Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

[Explore o Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)