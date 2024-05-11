# safe-route-ai
Colab para ajudar pessoas no RS a irem de cidades com risco de inundação para cidades de maior altitude

## Passos

1. Instalamos o SDK do Gooogle
2. Configuramos API KEY do Google Gemini
3. Carregamos o mapa topográfico do Rio Grande do Sul (https://github.com/luiseufrasio/safe-route-ai/blob/main/images/RS-Metropolitana.png):

	![image](https://github.com/luiseufrasio/safe-route-ai/assets/1511708/c12b87b2-3228-4244-8c6f-9924d82d327c)
   
4. Configuração do Modelo
5. Solicitamos ao modelo: "Analise esse mapa TOPOGRÁFICO de cores do Rio Grande de Sul, tente identificar as cidades que estão nele e me dê sua altitude aproximada com base nas cores. Mostre o resultado ordenado pela altitude encontrada."
6. Exibimos a resposta do Modelo:

	![image](https://github.com/luiseufrasio/safe-route-ai/assets/1511708/f6113da8-74c4-4dea-90b5-a06088984bef)

7. Pedimos ao User que informe em qual cidade está:

		Ex: Em qual dessas cidades você está: [Canoas, Lajeado, Pelotas, Porto Alegre, Rio Grande, São Leopoldo] ?	Porto Alegre

8. Solicitamos ao modelo que trace rotas da cidade escolhida para 3 cidades de uma lista de possíveis destinos:

		['Torres', 'São Francisco de Paula', 'Canela', 'Três Coroas', 'Igrejinha', 'Taquara', 'Rolante', 'Osório', 'Santo Antônio da Patrulha', 'Tramandaí']

10. Exibimos as rotas traçadas pelo Modelo:

	![image](https://github.com/luiseufrasio/safe-route-ai/assets/1511708/7e2ad267-aadc-4c28-aa97-7eebcac5a258)

11. Criamos um Chat passando o histórico do que já foi conversado com o modelo. Exemplo:
	![image](https://github.com/luiseufrasio/safe-route-ai/assets/1511708/8996326e-5825-44f6-b27c-6ba6c3ff95e1)


