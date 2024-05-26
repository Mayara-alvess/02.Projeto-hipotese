⚡ **Projeto hipotese**

## O que é o projeto?

Este projeto é o 2 desenvolvido no bootcamp da Laboratória, onde mergulhamos em análise de dados. Durante o curso, desenvolvemos sete projetos que aplicam os conhecimentos adquiridos.


## Contexto

Num mundo onde a indústria musical é extremamente competitiva e em constante evolução, a capacidade de tomar decisões baseadas em dados tornou-se um ativo inestimável. 

Uma gravadora enfrenta o emocionante desafio de lançar um novo artista no cenário musical global. 

Felizmente, ela tem uma ferramenta poderosa em seu arsenal: um extenso conjunto de dados do Spotify com informações sobre as músicas mais ouvidas em 2023.

## Objetivo

Validar as hipóteses através da análise de dados e fornecer recomendações estratégicas com base nas descobertas e tomar decisões informadas que aumentem as chances de alcançar o “sucesso”.

## Hipóteses

Músicas com BPM (Batidas Por Minuto) mais altos fazem mais sucesso em termos de número de streams no Spotify.

A presença de uma música em um maior número de playlists está correlacionada com um maior número de streams.

Artistas com um maior número de músicas no Spotify têm mais streams.

As características da música influenciam o sucesso em termos de número de streams no Spotify.

<details>
  <summary><strong>Obtenção dos dados</strong></summary>
  
### Para esse projeto foi disponibilizado pela Laboratoria 3 tabelas
  
  **Trackinspotify**
  
  track_id: Identificador exclusivo da música. É um número inteiro de 7 dígitos que não se repete.
  
  track_name: Nome da música.

  <strong>artist(s)_name</strong>: Nome do(s) artista(s) da música.
  
  artist_count: Número de artistas que contribuíram na música.
  
  released_year: Ano em que a música foi lançada.
  
  released_month: Mês em que a música foi lançada.
  
  released_day: Dia do mês em que a música foi lançada.
  
  inspotifyplaylists: Número de listas de reprodução do Spotify em que a música está incluída
  
  inspotifycharts: Presença e posição da música nas paradas do Spotify
  
  streams: Número total de streams no Spotify. Representa o número de vezes que a música foi ouvida.
  
  **Trackincompetition**
  
  track_id: Identificador exclusivo da música. É um número inteiro de 7 dígitos que não se repete.
  
  inappleplaylists: número de listas de reprodução da Apple Music em que a música está incluída.
  
  inapplecharts: Presença e classificação da música nas paradas da Apple Music.
  
  indeezerplaylists: Número de playlists do Deezer em que a música está incluída.
  
  indeezercharts: Presença e posição da música nas paradas da Deezer.
  
  inshazamcharts: Presença e classificação da música nas paradas da Shazam.
  
  **Tracktechnicalinfo**
  
  track_id: Identificador exclusivo da música. É um número inteiro de 7 dígitos que não se repete.

  bpm: Batidas por minuto, uma medida do tempo da música.

  key: Tom musical da música.

  mode: Modo de música (maior ou menor).

  danceability_%: Porcentagem que indica o quão apropriado a canção é para dançar

  valence_%: Positividade do conteúdo musical da música.

  energy_%: Nível de energia percebido da música.

  acusticness_%: Quantidade de som acústico na música.

  instrumentality_%: Quantidade de conteúdo instrumental na música.

  liveness_%: Presença de elementos de performance ao vivo.

  speechiness_%: Quantidade de palavras faladas na música.
</details>


## Conclusão

Descobrimos que um alto BPM (batidas por minuto) não está necessariamente relacionado ao sucesso de uma música. No entanto, notamos uma correlação entre o número de streams e a inclusão da música em playlists. Além disso, observamos uma relação entre o número de músicas lançadas por um cantor e o total de streams recebidos por ele. Cantores com um maior volume de lançamentos tendem a acumular mais streams apontando que a frequencia de lançamentos pode ser um fator para o sucesso na plataforma. Apesar de identificarmos algumas correlações entre características musicais, não encontramos evidências sólidas de uma ligação direta entre essas características e o sucesso de uma música.

## Recomendações

1.Lançar um maior número de músicas, porém de forma estratégica, pode ampliar o alcance e impulsionar o número de streams.

2.Parcerias Estratégicas: Estabelecer parcerias  pode ser uma maneira poderosa de aumentar a visibilidade da música. Essas parcerias não apenas ampliam a divulgação da música, mas também podem resultar na inclusão em um maior número de playlists, proporcionando maior exposição e oportunidades de descoberta para os ouvintes.

Essas recomendações podem levar a um aumento significativo no número de playlists e no volume de streams, especialmente quando combinadas com lançamentos planejados e estratégicos.

É importante destacar que, embora seguir as recomendações para criar a música perfeita seja crucial, isso por si só não garante o sucesso. Existem fatores externos, como tendências de mercado e comportamento do público, que podem influenciar significativamente o desempenho e a receptividade de uma música. Portanto, adotar uma abordagem flexível e adaptável é essencial para o artista ter chances de sucesso na indústria musical.

## Dashboard
![](https://github.com/Mayara-alvess/02.Projeto-hipotese/blob/main/Dashboard.png)

## Diretório

- Nas pastas, você encontrará as consultas realizadas através do BigQuery, bem como o ambiente do Google Colab, onde executei os códigos em Python e a documentação mais detalhada.

