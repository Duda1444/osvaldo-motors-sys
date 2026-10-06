## Osvaldo Motors

### Introdução
A Osvaldo Motors é uma oficina mecânica. O objetivo do sistema é facilitar o registro de serviços e peças, o cadastro de clientes e veículos, o histórico de ordens de serviço e o controle de débitos.


## Entidades

-> Cliente_Veículo
-> Ordem_Serviço

## Atributos

-> Cliente_Veículo:

• id_cliente
• nome 
• contato (Telefone)
• dados_veiculo 

-> Ordem_Serviço

• id_OS
• id_cliente
• data_Serviço
• servico_e_valores (ex: "Troca de óleo R$150 + Filtro R$50")
• valor_total 
• status_pagamento ( "Pago" ou "Fiado")

## Relacionamento

-> O realcionamento é de 1:N, pois um cliente pode pedir muitas ordens de serviço, mas uma ordem de serviço pertence a só um cliente.

## DER

![alt text](<Captura de tela 2026-10-06 154415.png>)

**Cliente:** Seu Osvaldo - Osvaldo Motors.
