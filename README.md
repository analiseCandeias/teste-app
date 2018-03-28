# teste-app

Neste teste, você deverá produzir uma aplicação nativa iOS ou Android que consuma o serviço de busca de cidades e hotéis do Candeias e exiba os resultados em português numa lista respeitando a ordem do retorno do serviço.

A lista deverá ser atualizada automaticamente quando o usuário digitar algum termo (o usuário não deverá clicar qualquer botão de envio para ver os resultados).

Você poderá utilizar quaisquer bibliotecas que julgar necessárias. Testes de unidade e integração devem ser implementados.

Exemplo de requisição para o serviço:

https://dev.clubecandeias.com/v1/hotels/autocomplete?search=Curitiba

Exemplo de resposta:


```json
{
    "suggestions": [
        {
            "id": 1112002,
            "hotel_id": null,
            "value": "Curitiba, Brasil",
            "english_value": "Curitiba, Brazil"
        }
    ]
}
```
