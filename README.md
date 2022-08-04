# DESAFIO MASTERCLASS

A ideia aqui é que você tente reproduzir aquilo que vimos durante a Masterclass e também construir o restante do código (usando TDD :heart_eyes: ) para cumprir os demais requisitos.

> Bora lá!? 🚀

## Estória (User Storie)

 - Atualmente trabalhamos apenas com os cartões AMEX e VISA para os custeios com a tripulação.
 - Considerando a inoperabilidade desses cartões em alguns países, optamos por incluir o cartão Mastecard.
 - Os custeios do novo cartão serão obtidos em um arquivo txt e os dados deverão ser parseados para utilização dos sistema de Expenses e Portal Employee.  
 - Formato do novo arquivo:

|DATA|VALUE|CURRENCY|STATUS|CARDNUMBER|COUNTRY|
|:----:|:-----:|:--------:|:------:|:----------:|:-------:|
|1-8|9-20|21-23|24|25-40|41-43|
|AAAA/MM/DD|VALUE|978|1|CARDNUMBER| 55-BRA

- STATUS
    - 1 PAGAMENTO EFETUADO
    - 2 PAGAMENTO CANCELADO
    - 3 ESTORNO DO PAGAMENTO

- CURRENCY 
    - [ISO-4217](https://pt.iban.com/currency-codes)
    - EUR : 978
    - BRL : 986
    - USD : 840 
 - COUNTRY
    - [ISO - 3166-1](https://www.iso.org/obp/ui/#search)
        - BRA : 076
        - USA : 840
        - GBR : 826


