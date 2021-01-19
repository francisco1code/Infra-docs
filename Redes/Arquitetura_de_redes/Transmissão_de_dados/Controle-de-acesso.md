# Mecanismo de acesso ao meio

## Contenção
Existe 2 tipode s algoritimos para aplicação de conteção

|Sigla| Significado | Uso | Caracteristicas| 
|-----|--------|--------|-----|
| CSMA/CD  | Carrier-Sense Multiple Acess with Collision Detection   | Usando redes Ethernet  | Não evita-se colisão |
| CSMA/CA  | Carrier-Sense Multiple Acess with Collision Avoidance  | Usando redes Wi-Fi  | evita-se colisão


# Métodos de Trasmissão

|Metodo | Canal |
|-------|-------|
| Transmissão em serie | Ultiliza um único canal |
| Trasmissão em paralelo| Ultiliza mais de um canal


# Multiplexação

## MUltiplexação por divisão espacial
Usa canais separados para cada transmissão. Exemplos de uso em redes:

* O uso de cabo de rede individual para conectar cada máquina em redes em topologia em
estrela com o uso de um switch.

* Máquina com dois cabos de rede (teaming).

* O uso de múltiplas antenas em redes sem fio, com transmissões diferentes ocorrendo em
paralelo. Tal técnica é denominada MIMO (Multiple Input, Multiple Output).

## Multiplexação por divisão de tempo

* Nesta técnica, o canal é liberado para transmitir um pouco de cada transmissão por vez. É a técnica
mais utilizada em redes tanto cabeadas quanto sem fio para se ter acesso ao meio.
Analogia: várias pessoas em uma mesma sala, apenas uma falando por vez.

## Multiplexação por divisão de frequência

* Utiliza frequências diferentes para obter transmissões simultâneas. O melhor exemplo de uso é o da
transmissão analógica de rádio, TV e TV a cabo.
Redes Wi-Fi, 4G e de transmissão de TV digital utilizam uma versão deste tipo de multiplexação
denominada multiplexação por divisão de frequência ortogonal (OFDM, Orthogonal Frequency-
Division Mutiplexing e OFDMA, Orthogonal Frequency Division Multiple Access), onde o canal é
subdividido em subcanais para a transmissão de dados em paralelo, a fim de aumentar a largura de
banda.
Analogia: várias pessoas em uma mesma sala, cada uma falando a um tom diferente.

## Multiplexação por divisão de código

* Nesta técnica, usada por redes Wi-Fi muito antigas (IEEE 802.11-1997 e IEEE 802.11b) e redes de
telefonia celular 2G e 3G, é utilizada uma faixa de frequência alargada em vez de um canal com
frequência estreita como ocorre na FDM/FDMA. Os dados são embaralhados com um código (uma
forma de onda) que é diferente para cada usuário (transmissor) e todos os dados são transmitidos
juntos. Na ponta receptora, só quem sabe o código tem acesso ao dado correspondente.
Analogia: várias pessoas em uma mesma sala, cada uma falando um idioma diferente.

## Multiplexação por divisão de comprimento de onda

* Técnica utilizada por fibras ópticas monomodo do tipo NZ-DSF (Non-Zero Dispersion-Shifted Fiber),
onde comprimentos de onda (cores) diferentes são usados para permitir fluxos de dados
independentes simultaneamente. É uma técnica análoga à multiplexação por divisão de frequência,
só que para fibras ópticas.
Analogia: várias pessoas em uma mesma sala, apenas as com roupa de mesma cor se falam.

 


