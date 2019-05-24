# Widesoftware - Fullstack challenge
O usuário deseja receber sugestões de músicas de acordo com a temperatura local de alguma cidade específica.
Pra isso precisamos criar um microserviço que aceite solicitações RESTful onde receberá por parâmetro o nome da cidade e retorne uma sugestão de músicas de acordo com a temperatura local.
Como exibição, podemos criar uma página (SPA - single-page application) que contenha um campo para que o usuário informe o nome da cidade e obtenha a sugestão de músicas. 

## Regras de negócio
- Se a temperatura (em celsius) estiver acima de 30 graus, sugerir músicas de categoria **Festa**.
- Caso a temperatura esteja entre 21 e 30 graus, sugerir músicas de categoria **Hip Hop**.
- Se estiver um pouco frio, entre 15 e 20 graus, sugira músicas de categoria **Clássica**.
- Agora, se estiver muito frio, abaixo de 15 graus, a sugestão é músicas de categoria **Rock**.

## Dicas
Você pode usar a API do **OpenWeatherMaps** (https://openweathermap.org) para pegar os dados de temperatura e a API do **Spotify** (https://developer.spotify.com) para pegar as msica que irá sugerir.
Para o Frontend sinta-se à vontade para utilizar Bootstrap ou até mesmo alguma biblioteca javascript, como React.js por exemplo.

## O que avaliaremos?
- Qualidade do código.
- Tratamento de erros.
- Testes no código (TDD).

## Será um diferencial
- Enviar o projeto em Docker.
- Teste de integração.

Gostaríamos também que descrevesse os detalhes da arquitetura e padrões utilizados na criação do projeto.
Por fim, compartilhe o seu código conosco via GitHub (público).
