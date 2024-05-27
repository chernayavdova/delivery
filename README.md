# Custo e Rentabilidade do Delivery de Comidas

Análise em Python e Power Bi de um dataset de delivery de comidas.


Como o nome já diz, nessa analise trago o custo e rentabilidade.

### Metodologia

#### Python 

Utilizei Python para ter uma visão geral do dataset,  procurar valores nulos, outliers e para converter a moeda, como o dataset é de um delivery de Nova Dehli, a moeda usada foi a indiana, então, converti para dólar, por isso os valores podem parecer abaixo.
Criei mais três colunas com a conversão da moeda


#### Power Bi

Criei o dashboard no Power Bi, além das colunas que já existiam, utilizei DAX para criar mais quatro e dar mais fluidez a análise.
Utilizei as fomulas IF, SUMX, FORMAT e HOUR.
   - Criei uma coluna chamada "Turno", nela utilizei o IF para ter melhor visão dos turnos dos pedidos.
     ![Captura de tela 2024-05-25 203207](https://github.com/chernayavdova/delivery/assets/86575159/04c369a3-d190-4003-b7d4-47a3f361e378)

   - Coluna "Hora" para saber os horários de pedidos e ver os horários de pico.
![Captura de tela 2024-05-25 203157](https://github.com/chernayavdova/delivery/assets/86575159/25bddb78-885f-4d16-b0e1-6fa6e7cb47e1)

   - Coluna "Calendar" para conseguir visualizar as vendas nos dias da semana e ver quais tem uma maior procura.
![Captura de tela 2024-05-25 203146](https://github.com/chernayavdova/delivery/assets/86575159/7c1253ef-b7d7-45ea-adcc-c2872bd490cb)

   - Coluna com a soma das colunas de entrega e comissão para ter uma ideia do custo.
![Captura de tela 2024-05-25 203215](https://github.com/chernayavdova/delivery/assets/86575159/2590e97c-859e-4f41-8280-b907cfdbde58)

   ##### Dashboard
   ![Captura de tela 2024-05-27 172550](https://github.com/chernayavdova/delivery/assets/86575159/079e715e-cc7b-4802-941e-a62885797472)

   - Podemos ver que de 5 ás 10 da manhã mantemos um nível similar de pedidos por hora, e temos picos às 17h da tarde e às 19h da noite .
   - O cupom mais usado é o de 10% e a promoção de 50 off
   - Os dias com mais pedidos são terça e sábado e os com menos são sexta e domingo. Isso pode acontecer pela distribuião de cupom, talvez eles sejam gerados nesses dias.

   #### Possíveis soluções

   - Vimos que, apesar de satisfátoria, as vendas em determinados dias e horários, principalmente no almoço, são bem menores, podemos contratar soluções de marketing, desconto por indicação de amigo, fidelizar no restaurante e ganhar cupons a partir de um certo numero de pedidos em um determinado período de tempo.

