# VPN(Virtual Private Network)

Permite a criação de uma rede privada segura entre dois pontos utilizando uma rede pública
insegura. Estes dois pontos podem ser:

* Duas redes
* Uma máquina e uma rede
* Duas máquinas

Aplicações práticas:
1. Site-to-site: conceito original. Utiliza o protocolo IPsec (Camada 3 do modelo OSI, isto é,
camada de Rede). Exemplos de uso: conexões entre duas redes ou extranet.
2. Servidor VPN: serviço análogo ao de proxy. Objetivos: burlar restrições de acesso
(geográficas ou de firewall), privacidade e criptografia. Existem dois tipos:
a. SSL: acessado usando um plugin adicionado ao navegador de Internet, opera na
camada 6 do modelo OSI, isto é, camada de Apresentação, utilizando o protocolo
TLS. Normalmente ativado apenas no acesso a alguns sites.
b. IPsec: acessado usando software próprio, opera na camada 3 do modelo OSI, isto é,
camada de Rede, utilizando o protocolo IPsec. Neste tipo de programa, o túnel VPN
pode ser ativado para apenas alguns sites, servidores ou serviços, ou pode ser
ativado para todo o tráfego.


Nota: o protocolo SSL não existe mais desde 2011, tendo sido substituído pelo protocolo TLS e,
portanto, a nomenclatura “SSL” está tecnicamente incorreta, embora seja usada comercialmente.

Diferenças na pratica de um Servidor VPN  e Servidor Proxy


|VPN | Proxy|
|----|----|
|Criptografia Obrigatoria | Criptografia Opcional|
|Normalmente intermedia apenas tráfego web | Pode intermedia todo tipo de tráfego |


