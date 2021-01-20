# Protocolo

## Modelo OSI (Camadas)
#### Pilha de protocolo

* 7- Aplicação
* 6- Apresentação
* 5- Sessão
* 4- Trasporte
* 3- Rede
* 2- Link de dados
* 1- Fisica


## PDU e SAP

### Protocol Data Unit(PDU)

Pacote de dados que é criado em cada camada do modelo OSI. Dependendo do contexto recebe um
nome diferente: segmento, datagrama, quadro, célula etc. “Pacote de dados” é o nome genérico.
O PDU da camada superior é encapsulado dentro da área de dados do PDU da camada atual.

### Service Access Point (SAP)
Faz a interface entre camadas do modelo OSI. É um sistema de endereçamento para saber qual
protocolo imediatamente acima da camada atual gerou os dados, para que no destino a área de
dados da camada atual seja entregue ao protocolo correto na camada imediatamente acima dela.
Exemplos práticos:

* Camada 2: endereço físico (endereço MAC) e EtherType
* Camada 3: endereço lógico (endereço IP) e número do protocolo
*  Camada 4: porta


